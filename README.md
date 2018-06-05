
# react-native-code-verification
This module presents you view with digit display and numkeypad for convinient entering

## Getting started

`$ npm i react-native-code-verification --save`


## Screenshots
<img src="/screenshots/second.png?raw=true" width="30%"> 

## Usage
```javascript
import Pincode from 'react-native-code-verification';

// TODO: What to do with the module?
class Example extends Component<IProps> {
  public render() {
    return (
      <View style={styles.container}>
        <Pincode onEnteredPincode={pin => this.onDetectPin(pin)} />
      </View>
    );
  }
  private onDetectPin = pin => {
    console.log('pinCode>>>', pin);
  };
}
```

### Props
| Name | Type | Description | Default |
| ---- | :---: | --- | --- |
| ```descriptionText``` | String  | A description text under digit | Please enter pincode for entry
| ```onEnteredPincode``` | Function  | A function that returns entered code | -
<<<<<<< HEAD
| ```onCloseView``` | Function  | On press close button, will be useful to close view | -
| ```onPressTouchId``` | Function  | Touch Id is not available, but you can make it by yourself | -
=======
| ```onCloseView``` | Function  | Called when pressed close button| -
>>>>>>> 44b5387d7835e81ebfb241c3eb8b143bd2c2624b

## Credentials
© [Otel Danagul](https://github.com/danchokobo)
