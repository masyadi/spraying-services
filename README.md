# @pakjarot/spraying-services

Library for srpaying services

## Installation


```sh
npm install @pakjarot/spraying-services
```


## Usage

- Registrasikan didalam navigation

```js
import { registerSprayingServiceRoutes } from '@pakjarot/spraying-services';

// ...
<NavigationContainer>
  <Stack.Navigator>
    ...

    {registerSprayingServiceRoutes({Stack: Stack})}
  </Stack.Navigator>
</NavigationContainer>
```

- Gunakan navigation

```js
import { Routes } from '@pakjarot/spraying-services';

// ...
<Button
  title="Jasa Semprot"
  onPress={() => {
    navigation.navigate(Routes.ScreenHome);
  }}
/>
```


## Contributing

- [Development workflow](CONTRIBUTING.md#development-workflow)
- [Sending a pull request](CONTRIBUTING.md#sending-a-pull-request)
- [Code of conduct](CODE_OF_CONDUCT.md)

## License

MIT

---

Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)
