# Vue application stack for Kubernetes on Wodby

Deploy Vue applications on Kubernetes with [Wodby](https://wodby.com).

<!-- wodby:generated:start -->

## Stack contract

- [Vue stack on Wodby](https://wodby.com/stacks/vue)
- [Browse Wodby application stacks](https://wodby.com/stacks)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## Start from a boilerplate

Use one of the compatible boilerplates exposed by this stack's services to
start with Wodby CI build configuration:

- [Vue boilerplate](https://github.com/wodby/vue-boilerplate)

## Service definitions

- [Nginx (Vue) service](https://github.com/wodby/service-vue)

## What's included

| Component / service | Default configuration |
| --- | --- |
| Nginx<br>`vue` | required; enabled by default |

Enabled optional services are selected by default but can be excluded when an
app is created. Disabled optional services are available but not selected by
default. Required services cannot be excluded.

## Validate the stack manifest

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

<!-- wodby:generated:end -->
