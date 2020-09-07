>#  Alexander Novikov 

* Contacts :

1. [vkontakte](https://vk.com/overnovik) 
2. [nerevarin11@gmail.com](https://mail.google.com/)
3. +37512345678

***

* Summary :
 I want to become a front-end developer, increase my knowledge in the field of IT

 ***

* Skills: OOP, HTML, CSS, JavaScript, Git, VSCode

***

* Code examples : 
```
const createStore = (initialState, reducer) => {
    let state = initialState;
    let subscribers = [];
    return {
        dispatch: (action) => {
            state = reducer(state, action);
            subscribers.forEach((fn)=>fn());
        },
        getState: () => state,
        subscribe: (fn) => subscribers.push(fn)
    }
}
```
***

* Experience : no experience in IT

***

* Education : HTMLacademy, Belarusian State Agrarian
Technical University, «GAS-INSTITUTE»

***

* English :  self-education A2