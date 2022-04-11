# @xstate/inspect

## 1.0.0-next.0

### Patch Changes

- [#898](https://github.com/statelyai/xstate/pull/898) [`c9cda27cb`](https://github.com/statelyai/xstate/commit/c9cda27cbe52b9c706ccb63b709d22d049be31e3) Thanks [@davidkpiano](https://github.com/davidkpiano)! - Fix crash when sending circular state objects (#2373).

- Updated dependencies [[`7f3b84816`](https://github.com/statelyai/xstate/commit/7f3b84816564d951b6b29afdd7075256f1f59501), [`969a2f4fc`](https://github.com/statelyai/xstate/commit/969a2f4fc0bc9147b9a52da25306e5c13b97f159), [`c0a6dcafa`](https://github.com/statelyai/xstate/commit/c0a6dcafa1a11a5ff1660b57e0728675f155c292), [`172d6a7e1`](https://github.com/statelyai/xstate/commit/172d6a7e1e4ab0fa73485f76c52675be8a1f3362), [`31bc73e05`](https://github.com/statelyai/xstate/commit/31bc73e05692f29301f5bb5cb4b87b90773e0ef2), [`e09efc720`](https://github.com/statelyai/xstate/commit/e09efc720f05246b692d0fdf17cf5d8ac0344ee6), [`145539c4c`](https://github.com/statelyai/xstate/commit/145539c4cfe1bde5aac247792622428e44342dd6), [`3de36bb24`](https://github.com/statelyai/xstate/commit/3de36bb24e8f59f54d571bf587407b1b6a9856e0), [`9e10660ec`](https://github.com/statelyai/xstate/commit/9e10660ec2f1e89cbb09a1094edb4f6b8a273a99), [`8fcbddd51`](https://github.com/statelyai/xstate/commit/8fcbddd51d66716ab1d326d934566a7664a4e175), [`515cdc9c1`](https://github.com/statelyai/xstate/commit/515cdc9c148a3a1b558120c309080e9a21e876bc), [`97b05690c`](https://github.com/statelyai/xstate/commit/97b05690cd8b30824eb176c813a145d3ef0d2a78), [`6043a1c28`](https://github.com/statelyai/xstate/commit/6043a1c28d21ff8cbabc420a6817a02a1a54fcc8), [`6a6b2b869`](https://github.com/statelyai/xstate/commit/6a6b2b8691626112d1d9dbf23d0a0e80ff7130a8), [`0b49437b1`](https://github.com/statelyai/xstate/commit/0b49437b1be3e6d9bc61304711b83300cba88dc4), [`0e24ea6d6`](https://github.com/statelyai/xstate/commit/0e24ea6d62a5c1a8b7e365f2252dc930d94997c4), [`04e89f90f`](https://github.com/statelyai/xstate/commit/04e89f90f97fe25a45b5908c45f25a513f0fd70f), [`0096d9f7a`](https://github.com/statelyai/xstate/commit/0096d9f7afda7546fc7b1d5fdd1546f55c32bfe4), [`8fcbddd51`](https://github.com/statelyai/xstate/commit/8fcbddd51d66716ab1d326d934566a7664a4e175), [`b200e0e0b`](https://github.com/statelyai/xstate/commit/b200e0e0b7123797086080b75abdfcf2fce45253), [`9437c3de9`](https://github.com/statelyai/xstate/commit/9437c3de912c2a38c04798cbb94f267a1e5db3f8), [`0038c7b1e`](https://github.com/statelyai/xstate/commit/0038c7b1e2050fe7262849aab8fdff4a7ce7cf92), [`b24e47b9e`](https://github.com/statelyai/xstate/commit/b24e47b9e7a59a5b0527d4386cea3af16c84ca7a), [`390eaaa52`](https://github.com/statelyai/xstate/commit/390eaaa523cb0dd243e39c6300e671606c1e45fc), [`0c6cfee9a`](https://github.com/statelyai/xstate/commit/0c6cfee9a6d603aa1756e3a6d0f76d4da1486caf), [`e09efc720`](https://github.com/statelyai/xstate/commit/e09efc720f05246b692d0fdf17cf5d8ac0344ee6), [`025a2d6a2`](https://github.com/statelyai/xstate/commit/025a2d6a295359a746bee6ffc2953ccc51a6aaad), [`e09efc720`](https://github.com/statelyai/xstate/commit/e09efc720f05246b692d0fdf17cf5d8ac0344ee6), [`c99bb43af`](https://github.com/statelyai/xstate/commit/c99bb43afec01ddee86fc746c346ea1aeeca687d), [`fc5ca7b7f`](https://github.com/statelyai/xstate/commit/fc5ca7b7fcd2d7821ce2409743c50505529104e7), [`c9cda27cb`](https://github.com/statelyai/xstate/commit/c9cda27cbe52b9c706ccb63b709d22d049be31e3), [`5d16a7365`](https://github.com/statelyai/xstate/commit/5d16a73651e97dd0228c5215cb2452a4d9951118), [`8fcbddd51`](https://github.com/statelyai/xstate/commit/8fcbddd51d66716ab1d326d934566a7664a4e175), [`53a594e9a`](https://github.com/statelyai/xstate/commit/53a594e9a1b49ccb1121048a5784676f83950024), [`31a0d890f`](https://github.com/statelyai/xstate/commit/31a0d890f55d8f0b06772c9fd510b18302b76ebb)]:
  - xstate@5.0.0-next.0

## 0.6.5

### Patch Changes

- [#3198](https://github.com/statelyai/xstate/pull/3198) [`09e2130df`](https://github.com/statelyai/xstate/commit/09e2130dff80815c10df38496a761fe8ae0d9f6e) Thanks [@Andarist](https://github.com/Andarist)! - Fixed an issue that prevented some states from being sent correctly to the inspector when serializable values hold references to objects throwing on `toJSON` property access (like `obj.toJSON`). This property is accessed by the native algorithm before the value gets passed to the custom `serializer`. Because of a bug we couldn't correctly serialize such values even when a custom `serializer` was implemented that was meant to replace it in a custom way from within its parent's level.

* [#3199](https://github.com/statelyai/xstate/pull/3199) [`f3d63147d`](https://github.com/statelyai/xstate/commit/f3d63147d36791344d55fa9c945af32daeefa2fa) Thanks [@Andarist](https://github.com/Andarist)! - Fixed an issue that caused sending the same event multiple times to the inspector for restarted services.

- [#3076](https://github.com/statelyai/xstate/pull/3076) [`34f3d9be7`](https://github.com/statelyai/xstate/commit/34f3d9be74d2bd9db51b2db06c5a65d980aec9c4) Thanks [@SimeonC](https://github.com/SimeonC)! - Fixed an issue with "maximum call stack size exceeded" errors being thrown when registering a machine with a very deep object in its context despite using a serializer capable of replacing such an object.

## 0.6.4

### Patch Changes

- [#3144](https://github.com/statelyai/xstate/pull/3144) [`e08030faf`](https://github.com/statelyai/xstate/commit/e08030faf00e2bcb192040b6ba04178ecf057509) Thanks [@lecepin](https://github.com/lecepin)! - Added UMD build for this package that is available in the `dist` directory in the published package.

* [#3144](https://github.com/statelyai/xstate/pull/3144) [`e08030faf`](https://github.com/statelyai/xstate/commit/e08030faf00e2bcb192040b6ba04178ecf057509) Thanks [@lecepin](https://github.com/lecepin)! - Added proper `peerDependency` on XState. It was incorrectly omitted from the `package.json` of this package.

## 0.6.3

### Patch Changes

- [#3089](https://github.com/statelyai/xstate/pull/3089) [`862697e29`](https://github.com/statelyai/xstate/commit/862697e2990934d46050580d7e09c749d09d8426) Thanks [@Andarist](https://github.com/Andarist)! - Fixed compatibility with Skypack by exporting some shared utilities from root entry of XState and consuming them directly in other packages (this avoids accessing those things using deep imports and thus it avoids creating those compatibility problems).

## 0.6.2

### Patch Changes

- [#2957](https://github.com/statelyai/xstate/pull/2957) [`8550ddda7`](https://github.com/statelyai/xstate/commit/8550ddda73e2ad291e19173d7fa8d13e3336fbb9) Thanks [@davidkpiano](https://github.com/davidkpiano)! - The repository links have been updated from `github.com/davidkpiano` to `github.com/statelyai`.

## 0.6.1

### Patch Changes

- [#2907](https://github.com/statelyai/xstate/pull/2907) [`3a8eb6574`](https://github.com/statelyai/xstate/commit/3a8eb6574db51c3d02c900561be87a48fd9a973c) Thanks [@rossng](https://github.com/rossng)! - Fix crash when sending circular state objects (#2373).

## 0.6.0

### Minor Changes

- [#2640](https://github.com/statelyai/xstate/pull/2640) [`c73dfd655`](https://github.com/statelyai/xstate/commit/c73dfd655525546e59f00d0be88b80ab71239427) Thanks [@davidkpiano](https://github.com/statelyai)! - A serializer can now be specified as an option for `inspect(...)` in the `.serialize` property. It should be a [replacer function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify#the_replacer_parameter):

  ```js
  // ...

  inspect({
    // ...
    serialize: (key, value) => {
      if (value instanceof Map) {
        return 'map';
      }

      return value;
    }
  });

  // ...

  // Will be inspected as:
  // {
  //   type: 'EVENT_WITH_MAP',
  //   map: 'map'
  // }
  someService.send({
    type: 'EVENT_WITH_MAP',
    map: new Map()
  });
  ```

* [#2894](https://github.com/statelyai/xstate/pull/2894) [`8435c5b84`](https://github.com/statelyai/xstate/commit/8435c5b841e318c5d35dfea65242246dfb4b34f8) Thanks [@Andarist](https://github.com/Andarist)! - The package has been upgraded to be compatible with `ws@8.x`. The WS server created server-side has to be of a compatible version now.

## 0.5.2

### Patch Changes

- [#2827](https://github.com/statelyai/xstate/pull/2827) [`49de77085`](https://github.com/statelyai/xstate/commit/49de770856965b0acec846c1ff5c29463335aab0) Thanks [@erlendfh](https://github.com/erlendfh)! - Fixed a bug in `createWebsocketReceiver` so that it works as expected with a WebSocket connection.

## 0.5.1

### Patch Changes

- [#2728](https://github.com/statelyai/xstate/pull/2728) [`8171b3e12`](https://github.com/statelyai/xstate/commit/8171b3e127a289199bbcedb5cec839e9da0a1bb2) Thanks [@jacksteamdev](https://github.com/jacksteamdev)! - Fix server inspector to handle WebSocket messages as Buffer

## 0.5.0

### Minor Changes

- [`4f006ffc`](https://github.com/statelyai/xstate/commit/4f006ffc0d39854c77caf3c583bb0c9e058259af) [#2504](https://github.com/statelyai/xstate/pull/2504) Thanks [@Andarist](https://github.com/Andarist)! - `Inspector`'s `subscribe` callback will now get immediately called with the current state at the subscription time.

### Patch Changes

- [`e90b764e`](https://github.com/statelyai/xstate/commit/e90b764e4ead8bf11d273ee385a8c2db392251a4) [#2492](https://github.com/statelyai/xstate/pull/2492) Thanks [@Andarist](https://github.com/Andarist)! - Fixed a minor issue with sometimes sending `undefined` state to the inspector which resulted in an error being thrown in it when resolving the received state. The problem was very minor as no functionality was broken because of it.

## 0.4.1

### Patch Changes

- [`d9282107`](https://github.com/statelyai/xstate/commit/d9282107b931b867d9cd297ede71b55fe11eb74d) [#1800](https://github.com/statelyai/xstate/pull/1800) Thanks [@davidkpiano](https://github.com/statelyai)! - Fixed a bug where services were not being registered by the inspect client, affecting the ability to send events to inspected services.

## 0.4.0

### Minor Changes

- [`63ba888e`](https://github.com/statelyai/xstate/commit/63ba888e19bd2b72f9aad2c9cd36cde297e0ffe5) [#1770](https://github.com/statelyai/xstate/pull/1770) Thanks [@davidkpiano](https://github.com/statelyai)! - It is now easier for developers to create their own XState inspectors, and even inspect services offline.

  A **receiver** is an actor that receives inspector events from a source, such as `"service.register"`, `"service.state"`, `"service.event"`, etc. This update includes two receivers:

  - `createWindowReceiver` - listens to inspector events from a parent window (for both popup and iframe scenarios)
  - 🚧 `createWebSocketReceiver` (experimental) - listens to inspector events from a WebSocket server

  Here's how it works:

  **Application (browser) code**

  ```js
  import { inspect } from '@xstate/inspect';

  inspect(/* options */);

  // ...

  interpret(someMachine, { devTools: true }).start();
  ```

  **Inspector code**

  ```js
  import { createWindowReceiver } from '@xstate/inspect';

  const windowReceiver = createWindowReceiver(/* options? */);

  windowReceiver.subscribe(event => {
    // here, you will receive events like:
    // { type: "service.register", machine: ..., state: ..., sessionId: ... }
    console.log(event);
  });
  ```

  The events you will receive are `ParsedReceiverEvent` types:

  ```ts
  export type ParsedReceiverEvent =
    | {
        type: 'service.register';
        machine: StateMachine<any, any, any>;
        state: State<any, any>;
        id: string;
        sessionId: string;
        parent?: string;
        source?: string;
      }
    | { type: 'service.stop'; sessionId: string }
    | {
        type: 'service.state';
        state: State<any, any>;
        sessionId: string;
      }
    | { type: 'service.event'; event: SCXML.Event<any>; sessionId: string };
  ```

  Given these events, you can visualize the service machines and their states and events however you'd like.

## 0.3.0

### Minor Changes

- [`a473205d`](https://github.com/statelyai/xstate/commit/a473205d214563033cd250094d2344113755bd8b) [#1699](https://github.com/statelyai/xstate/pull/1699) Thanks [@davidkpiano](https://github.com/statelyai)! - The `@xstate/inspect` tool now uses [`fast-safe-stringify`](https://www.npmjs.com/package/fast-safe-stringify) for internal JSON stringification of machines, states, and events when regular `JSON.stringify()` fails (e.g., due to circular structures).

## 0.2.0

### Minor Changes

- [`1725333a`](https://github.com/statelyai/xstate/commit/1725333a6edcc5c1e178228aa869c907d3907be5) [#1599](https://github.com/statelyai/xstate/pull/1599) Thanks [@davidkpiano](https://github.com/statelyai)! - The `@xstate/inspect` package is now built with Rollup which has fixed an issue with TypeScript compiler inserting references to `this` in the top-level scope of the output modules and thus making it harder for some tools (like Rollup) to re-bundle dist files as `this` in modules (as they are always in strict mode) is `undefined`.
