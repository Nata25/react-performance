## `Epic React` workshop by [Kent C. Dodds](https://github.com/kentcdodds) 

[https://epicreact.dev/learn/](https://epicreact.dev/learn/)

### Part 5: React Performance

- code splitting: asynchronous module load with `React.Suspense`, `web worker` for heavy script tasks
- memoisation: pros and contras
- usecases for `React.memo` and `React.useMemo`, custom comparator function
- memoising Context
- techniques to improve state management and avoid unnecessary re-renders: state allocation, multiple global Contexts, props structure optimization
- split data managing and component's inner logic with HOC and original memoised component
- use `react-virtual` to render only a visible part of huge piece of data
- `recoil` as an alternative to centralised state management 

The most important part of the workshop was to explore instruments of monitoring React apps performance, such as:
- **Profiler** of React DevTools
- **Performance** tools in Google Chrome DevTools
- `React.Profiler` component with experimental `trace` tool
