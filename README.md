# Vue application stack for Kubernetes on Wodby

Deploy Vue applications on Kubernetes with [Wodby](https://wodby.com).

## Stack contract

- [Vue stack on Wodby](https://wodby.com/stacks/vue)
- [Vue service](https://github.com/wodby/service-vue)
- [Vue boilerplate](https://github.com/wodby/vue-boilerplate)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)

The stack contains one required main service. The Vue service inherits the Nginx runtime and exposes the Vue starter as its boilerplate.

## Validate the manifest

```sh
wodby stack validate-manifest stack.yml --org <org-id>
```

See the [stack manifest reference](https://wodby.com/docs/2.0/stacks/template/) and [managed stacks index](https://github.com/wodby/stacks).
