This is an attempt to demonstrate pnpm use with storybook 7.0 and the vite builder.

To start:

```
pnpm i
pnpm run storybook
```

There are still a handful of peer dependency warnings, but those don't cause any problems.  However, a vite error is shown when the storybook tries to launch, because it cannot find the dependencies where pnpm has put them.
