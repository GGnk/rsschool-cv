# Nurlan Kurbandurdyev - Junior Full Stack Developer
Russia, Saratov.

<a href="tel:+89675018187" title="Mobile phone">+89675018187</a>

<a href="mailto:nurlan.wap3@gmail.com" title="E-mail">nurlan.wap3@gmail.com</a> 

## Summary
Good afternoon,
My name is Nurlan.
I use web programming both in my work, for solving various tasks, and as a hobby.
I want to become a professional in the field of web technologies.

## Skills

- **HTML5**
- **CSS3**
- **Bootstrap**
- **JavaScript**
- **SASS(SCSS)**
- **Git**
- **NPM**
- **Vue.JS**
- **Webpack**
- **WebSockets**
- **Photoshop;**
- **Flexbox & basic of CSS Grid**
- **Redis**
- **PHP**
- **Laravel**
 **etc..**

## Code examples
```
let actions = {
    async INITIAL_BOOT({commit, dispatch}) {
        await axios.post('/initial')
            .then((info) => {
                commit('INITIAL_BOOT', info)
                commit('ACCESS_INFO')
                commit('LEFT_MENU')
                commit('UI_')
                dispatch('LOADER_MODULES')
            })
            .catch((err) => {
                console.log(err)
            })
    },
    INSPECTOR(){
        axios.interceptors.request.use(config => {
            state.console.push({module: 'INSPECTOR', message: 'Исходящий запрос на '+config.url })
            return config
        })
    },
    LOADER_MODULES({commit, dispatch, getters}) {
        if(getters['auth']) dispatch('tasks/FETCH_DATA', null, { root: true })
    }

}
```
```
let routes = [
    {
        path: '/',
        name: 'Dashboard',
        component: () => import('../views/Dashboard'),
        meta: {
            // requiresAuth: true
        }
    },
    {
        path: '/ver',
        name: 'Ver',
        component: () => import('../modules/Version/VerComponent'),
        meta: {
            // requiresAuth: true
        }
    },
    {
        path: '/file-manager',
        name: 'FileManager',
        component: () => import('../modules/FileManager/laravel-file-manager/src/FileManager'),
        meta: {
            // requiresAuth: true
        }
    },
]
export default routes
```

## Experience
I developed/refactored scripts and various modules both during freelancing and for my own tasks. One of the public projects can be seen about the link. https://github.com/GGnk/Workspace

At the moment I am actively studying Javascript and Vue.JS

## Education

Professional education in the field of system management (Computer networks and complexes).
Various online training and online services, example https://htmlacademy.ru/profile/id57898
## My english

I can read the documentation and can understand and use frequently-used everyday expressions as well as simple phrases to meet immediate needs.
