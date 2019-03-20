# On Vue's Docs

Vue's docs are often touted as really great.

I think there's lots of room for improvement, especially for jr developers.

Something like the [vm.\$children](https://vuejs.org/v2/api/#vm-children) details are great:

> The direct child components of the current instance. **Note there’s no order guarantee for `$children`, and it is not reactive**. If you find yourself trying to use `$children` for data binding, consider using an Array and `v-for` to generate child components, and use the Array as the source of truth.

This part is particularly great:

> If you find yourself trying to use `$children` for data binding, consider using an Array and `v-for` to generate child components, and use the Array as the source of truth.

Where I get lost/have difficulty in the Vue docs:

1. Include the different ways of writing the example code!

Examples are often given via writing vue apps not as single components but as straight up javascript objects. This seems to either be for sprinkling in vue, or for more experienced devs. True, you can get up and running quicker w/ the js way, via spinning up html w/ `<script src=""/>` tag. But writing apps means writing single file components. **For x ways there are to write vue, there should be x versions for each example in the docs where applicable**

2. Include the name of the file where this code example goes!

Put it in a comment at the top of the code example.
