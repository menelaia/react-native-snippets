# React Native Snippets for VS Code

Extension provides useful React/React Native snippets that will improve your developer experience.

## List of supported snippets

### React Native Components

### `rnf→`
```javascript
import React from 'react';
import { View, Text } from 'react-native';
import PropTypes from 'prop-types';

export function $1(props) {
  return (
    <View>
        <Text>$1</Text>
    </View>
  );
}

$1.propTypes = {
};

$1.defaultProps = {
};
```

### `rnfd→`
```javascript
import React from 'react';
import { View, Text } from 'react-native';
import PropTypes from 'prop-types';

export default function $1(props) {
  return (
    <View>
        <Text>$1</Text>
    </View>
  );
}

$1.propTypes = {
};

$1.defaultProps = {
};
```

### `rnfm→`
```javascript
import React from 'react';
import { View, Text } from 'react-native';
import PropTypes from 'prop-types';

export function $1(props) {
  return (
    <View>
        <Text>$1</Text>
    </View>
  );
}

$1.propTypes = {
};

$1.defaultProps = {
};

export default React.memo($1);
```

### PropTypes

|Shortcut|Method|
|-------:|-------|
|`ipt→`|`import PropTypes from 'prop-types';`|
|`pt→`|`Component.PropTypes = {};`|
|`dfp→`|`Component.defaultProps = {};`|
|`pta→`|`PropTypes.array`|
|`ptar→`|`PropTypes.array.isRequired`|
|`ptb→`|`PropTypes.bool`|
|`ptbr→`|`PropTypes.bool.isRequired`|
|`ptf→`|`PropTypes.func`|
|`ptfr→`|`PropTypes.func.isRequired`|
|`ptn→`|`PropTypes.number`|
|`ptnr→`|`PropTypes.number.isRequired`|
|`pto→`|`PropTypes.object`|
|`ptor→`|`PropTypes.object.isRequired`|
|`pts→`|`PropTypes.string`|
|`ptsr→`|`PropTypes.string.isRequired`|
|`ptnd→`|`PropTypes.node`|
|`ptndr→`|`PropTypes.node.isRequired`|
|`ptel→`|`PropTypes.element`|
|`ptelr→`|`PropTypes.element.isRequired`|
|`pti→`|`PropTypes.instanceOf(name)`|
|`ptir→`|`PropTypes.instanceOf(name).isRequired`|
|`ptone→`|`PropTypes.oneOf([name])`|
|`ptoner→`|`PropTypes.oneOf([name]).isRequired`|
|`ptonet→`|`PropTypes.oneOfType([name])`|
|`ptonetr→`|`PropTypes.oneOfType([name]).isRequired`|
|`ptao→`|`PropTypes.arrayOf(name)`|
|`ptaor→`|`PropTypes.arrayOf(name).isRequired`|
|`ptoo→`|`PropTypes.objectOf(name)`|
|`ptoor→`|`PropTypes.objectOf(name).isRequired`|
|`ptsh→`|`PropTypes.shape({ })`|
|`ptshr→`|`PropTypes.shape({ }).isRequired`|

### JavaScript

|Shortcut|Method|
|-------:|-------|
|`clg→`|`console.log()`|
