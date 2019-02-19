# rxjs-serial-subscription


[DEPRICATED] : The repo is not IE11 friendly, AND will unsubsribe subscriptions that used "Like" observables. RXJS remove isn't what it needs to be.. 

use, and wrap observables with the below 

export function serialize(obs$: Observable<any>) {
	return obs$.pipe(switchMap((sm) => of(sm)));
}



