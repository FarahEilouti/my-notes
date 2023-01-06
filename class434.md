# class 34
## _Context API_
#
#### Global state can be useful for storing data that needs to be shared across multiple components or modules in an application, but it can also be a source of complexity and bugs if not used carefully. Because global state is available to all parts of the application, it can be difficult to track where and how it is being modified, which can make it harder to understand the behavior of the application and to fix bugs when they arise.

#### "context" API is a way to pass data through the component tree without having to pass props down manually at every level. It is designed to make it easy to share values such as colors, fonts, or themes throughout an application, without the need to explicitly pass props through every level of the component tree.

#### Redux is based on the idea of a "single source of truth", which means that the state of the entire application is stored in a single object, called the "store". The store is managed by a set of reducer functions, which specify how the state of the application should be updated in response to actions.