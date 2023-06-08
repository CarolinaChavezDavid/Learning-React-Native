# Learning-React-Native
![image](https://github.com/CarolinaChavezDavid/Learning-React-Native/assets/77591347/f89e35f6-9ff3-4e79-9b10-b3a93e30c1d7)

| **React Js**                                                                    | **React-Native**                                                                                |
|---------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| JavaScript library for building Responsive User Interfaces in Web Application.  | It is a framework for creating mobile applications with a native feel.                          |
| React uses CSS animations on a major scale to achieve animations for a web page | The recommended way to animate a component is to use the Animated API provided by React-Native. |
|                                                                                 |                                                                                                 |

## Advantages
  * Large Community: Open source framework
  * Reusability: Code use in Android and iOS
  * Live and Hot Reloading: Reloads the entire app when a file changes without losing the state of the app
  * Additional Third-Party Plugins

## Threads
  * **MAIN/UI  Thread** — This is the main application thread on which your Android/iOS app is running. The UI of the application can be changed by the Main thread and it has access to it .
  * **Shadow Thread** — layout created using React library in React Native can be calculated by this and it is a background thread.
  * **JavaScript Thread** — The main Javascript code is executed by this thread.

## Layouts
  ### Flexbox
  Allows elements to align and distribute space within a container.
  | **Property**   | **Values**                                                          |
|----------------|---------------------------------------------------------------------|
| flexDirection  | ‘column’, 'row'                                                     |
| justifyContent | ‘center’, 'flex-start', 'flex-end', 'space-around', 'space-between' |
| alignItems     | center’, 'flex-start', 'flex-end', 'stretched'                      |

## Hooks
  ### State Hooks 
  (Remember user information)
  * useState declares a state variable that you can update directly.
  * useReducer declares a state variable with the update logic inside a reducer function.
    
   ### Efect Hooks
   lets a component receive information from distant parents without passing it as props.
* useEffect connects a component to an external system. (it's executed when the screen or component is launched)


## Redux
Redux is a predictable state container for JavaScript apps. It helps write applications that run in different environments. This means the entire data flow of the app is handled within a single container while persisting previous state.

  * **Actions**: are payloads of information that send data from your application to your store. They are the only source of information for the store. This means if any state change is necessary the change required will be dispatched through the actions.
  * **Reducers**: “Actions describe the fact that something happened, but don’t specify how the application’s state changes in response. This is the job of reducers.” when an action is dispatched for state change its the reducers duty to make the necessary changes to the state and return the new state of the application.
  * **Store**: a store can be created with help of reducers which holds the entire state of the application. The recommended way is to use a single store for the entire application rather than having multiple stores which will violate the use of redux which only has a single store.
  * **Components**: this is where the UI of the application is kept

## Navigation

* Stack Navigation:
  navigation.pop/popToTop/goBack
* Drawer Navigation
* BottomTab Navigation
* MaterialTop Navigation

## Context and global state



