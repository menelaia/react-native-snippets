# React Native Snippets for VS Code

[![Version](https://vsmarketplacebadge.apphb.com/version-short/menelaia.react-native-dev-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=Menelaia.react-native-dev-snippets)
[![Install](https://vsmarketplacebadge.apphb.com/installs-short/menelaia.react-native-dev-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=Menelaia.react-native-dev-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-star/menelaia.react-native-dev-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=Menelaia.react-native-dev-snippets)


Extension provides useful React/React Native snippets that will improve your developer experience.

## ✨ List of supported snippets

### 🗂️ React Native Components

#### React Native Functional Component with export, `rnf→`
```javascript
import React, { useCallback, useEffect, useMemo, useState } from 'react';
import { Text, View } from 'react-native';
import { useDispatch, useSelector } from 'react-redux';
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

#### React Native Functional Component with default export, `rnfd→`
```javascript
import React, { useCallback, useEffect, useMemo, useState } from 'react';
import { Text, View } from 'react-native';
import { useDispatch, useSelector } from 'react-redux';
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

#### React Native Functional Component with React.memo default export, `rnfm→`
```javascript
import React, { useCallback, useEffect, useMemo, useState } from 'react';
import { Text, View } from 'react-native';
import { useDispatch, useSelector } from 'react-redux';
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

### 📄 Hooks

|Hook|Shortcut|Method|
|------------|-------:|-------|
|`useEffect`|`uef→`|`useEffect(() => {$1}, [$2]);`|
|`useState`|`ust→`|`const [$1, $2] = useState($3);`|
|`useMemo`|`ume→`|`const $1 = useMemo(($2) => $3, [$4]);`|
|`useCallback`|`uca→`|`const $1 = useCallback(($2) => {$3}, [$4]);`|
|`useDispatch`|`udi→`|`const dispatch = useDispatch();`|
|`useSelector`|`usl→`|`const $1 = useSelector($2);`|

#### • useEffect, `uef→`
```javascript
useEffect(() => {
    $1
}, [$2]);
```

#### • useState, `ust→`
```javascript
const [$1, $2] = useState($3);
```

#### • useMemo, `ume→`
```javascript
const $1 = useMemo(($2) => $3, [$4]);
```

#### • useCallback, `uca→`
```javascript
const $1 = useCallback(($2) => {
    $3
}, [$4]);
```

#### • useDispatch, `udi→`
```javascript
const dispatch = useDispatch();
```

#### • useSelector, `usl→`
```javascript
const $1 = useSelector($2);
```

### 🗂️ PropTypes

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

### ⚡ JavaScript

|Shortcut|Method|
|-------:|-------|
|`clg→`|`console.log()`|
