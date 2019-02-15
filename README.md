# rxjs-serial-subscription

This is a reimplementation of RxJS 5.x's SerialSubscription for RxJS 6.x.


The problem this repo solves is this:

Even after all pipes, debounces and other operators you can add to rxjs, this is the simplest method to implement in regards to cancelling in flight requests, without having to implement custom subjects as cancellation tokens, manual and code convoluting subscription variables amongst other methods of cancelling in flight requests.
See the Wiki https://github.com/dontboyle/rxjs-serial-subscription/wiki for more information!


npm: https://www.npmjs.com/package/rxjs-serializable-subscription

npm install rxjs-serializable-subscription

yarn add rxjs-serializable-subscription

StackBlitz Implementation: https://stackblitz.com/edit/typescript-dswrjc
