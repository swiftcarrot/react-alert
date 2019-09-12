# react-alert

Alert for React and React Native

### Installation

```sh
yarn add @swiftcarrot/react-alert
```

### Usage

```javascript
import { showAlert, hideAlert } from '@swiftcarrot/react-alert';

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

### Styling

### License

MIT
