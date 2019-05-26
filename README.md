# Presentation Vue.js
`(Slide - Introduction)`  
My name is Elena Yanchenko. I'm a RSSchool student.  
`(Slide - logo Vue.js)`  
And I will tell you about Vue.js framework.  
`(Slide - Evan You)`  
The creator of Vue.js is Evan You, a former employee of Google and Meteor Dew Group. From 2016 he has been working full-time on Vue.js framework.  
`(Slide - History)`  
Evan You began to develop the framework in 2013. The first release took place in February 2014, in October 2015 v1.0 has been released. The latest version 2.6.10 released on March 20, 2019.  
`(Slide - Information)`  
Vue.js is a progressive framework, component oriented and mix the best React and Angular.  
`(Slide - Advantages)`  
Vue.js has a very small size compared to other frameworks.  
`(Slide - Easy to understand and develop application)`  
Vue.js is easy to understand and develop application. There is at Vue's core the system which allows to display DOM's data by using straightforward template syntax. This is like the code of a simple Vue app looks.  
`(Slide - Simple integration)`  
Vue.js simple integrates with other libraries or existing project.  
`(Slide - Detailed Documentation)`  
There is detailed Documentation on the official website <http://vuejs.org>.  
`(Slide - Flexibility)`  
Flexibility
<li> Write your template in an HTML file
<li> Write your template in a string in a Javascript file
<li> Use JSX in a Javascript file
<li> Make your template in pure Javascript using virtual nodes
  
This flexibility makes it easy to switch to Vue because React developers, Angular developers, or developers new to JS frameworks would all find Vue's design familiar.  
`(Slide - Right to Choose)`  
You can choose between a template or a component class.  
`(Slide - Ecosystem)`  
The ecosystem Vue.js includes projects  Vue-router,  Vuex, Vue-cli, Vue-loader, Vue-server-renderer, Vue-class-component, Vue-rx, Vue-devtools.   
`(Slide - Who is using it?)`  
Who is using it?
It is GitLab, NativeScript, Weex, Baidu, Xiaomi. The core of Laravel and Pagekit includes Vue.js.  
`(Slide - How it Works?)`  
How it Works?  
`(Slide - MVVM)`  
Every Vue application starts by creating a new Vue instance with the Vue function. As the base has taken MVVM pattern.  
`(Slide - Components)`  
Components are reusable Vue instances with they own name, so they accept the same options as new Vue. It’s common for an app to be organized into a tree of nested components.  
`(Slide - Lifecycle)`  
Lifecycle hooks give to users the opportunity to add their own code at specific stages. The slide shows a diagram for the instance lifecycle.  
`(Slide - Reactivity)`  
One of Vue's most distinct features is the unobtrusive reactivity system. Models are just plain JavaScript objects. When you modify them, the view updates. It makes state management simple and intuitive. You can see on the diagram haw changes are tracked.  
`(Slide - Interpolations)`   
Vue.js uses an HTML-based template syntax that allows you to declaratively bind the rendered DOM to the underlying Vue instance’s data.   
`(Slide - Text)`  
The most basic form of data binding is text interpolation using the "Mustache" syntax. The mustache tag will be replaced with the value of the variable property on the corresponding data object.     
`(Slide - Raw HTML)`   
You will need to use the v-html directive for output real HTML.   
`(Slide - Attributes)`  
Mustache cannot be used inside HTML attributes. Instead, use a v-bind directive.  
`(Slide - Using JavaScript Expressions)`  
This expressions will be valuated JavaScript in the data scope of the owner Vue instance. The limitation is that one binding can contain only one expression.  
`(Slide - Directives)`  
Directives are special attributes with the v- prefix. Directive attribute values are expected to be one JavaScript expression. Directive reactively applies changes to the DOM when the value of its expression changes. For example directives are v-bind, v-on and modifiers.  
`(Slide - Binding HTML Classes)`   
Vue provides special enhancements when v-bind is used with class and style. These attributes, in addition to string values, can take arrays or objects.  
`(Slide - Conditional Rendering)`  
The directives v-if, v-else-if are used to conditionally render a block. The block is rendered if the directive expression returns true.  
`(Slide - Loops)`  
You can use the v-for directive to render a list of items based on an array. 
`(Slide - Method Event Handlers)`  
You can use the v-on directive to subscribe to DOM events and some JavaScript runs when they're triggered.   
`(Slide - Form Input Bindings)` 
You can use the v-model directive to create two-way data bindings on form input, textarea, and select elements.  
`(Slide - Etc...)`  
More information is in the guide of using Vue.js.   
`(Slide - logo Vue.js)`  
Vue.js is amazing! I think it's great that I can just plug it in on the page and start working without setting up the build system or CLI. It's very easy to get started with it, even if you have never worked with JavaScript frameworks. It is the perfect combination of convenience and power.  
`(Slide - Thank you!)`  
Thank you!
