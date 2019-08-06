# react-native-alert

React native alert component for both iOS and Android

### Installation

```sh
yarn add @swiftcarrot/react-native-alert
```

### Usage

```javascript
import {
  Alert,
  showAlert,
  hideAlert,
  useAlert
} from '@swiftcarrot/react-native-alert';

const App = () => {
  return (
    <Alert.Provider>
      <Alert />
    </Alert.Provider>
  );
};

const Screen = () => {
  const { showAlert, hideAlert } = useAlert();

  return <View></View>;
};
```

```javascript
import { showAlert, hideAlert } from '@swiftcarrot/react-native-alert';

showAlert({
  title: 'title',
  subtitle: 'subtitle',
  styles: {
    title: {},
    subtitle: {}
  },
  buttons: [
    {
      text: 'ok',
      onPress: hideAlert
    }
  ]
});
```

### License

MIT
