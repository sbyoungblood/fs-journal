# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
One way binding uses v-bind: or ':' and data only flows one direction.

Two way binding uses a v-model and data can flow from the model to the vue layer, and back.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
They are much faster, and require less maintenance.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted does whatever is inside of it (typically invokes functions), immediately upon page load.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
v-model allows two way binding. Thus far, I've mostly used it in form inputs.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
@ attaches event listeners to elements on the dom, as in an @click on a button.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-else, and v-for....   and v-show, but not really.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
I'm not all too familiar with what 'key' does just yet, but I know it improves efficiency.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
the 'slot' defines placeholders in a components template that can then be filled with content from the parent component.
```