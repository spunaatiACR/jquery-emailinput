# jQuery-emailinput [![Build Status](https://travis-ci.org/jongha/jquery-emailinput.png?branch=master)](https://travis-ci.org/jongha/jquery-emailinput)

jQuery-emailinput is email address input control for jQuery. It is really simple.

## `Usage`

Initialize

```
$('#target').emailinput();
```

Change internally control id.

```
$('#target').emailinput( { id: 'changed id' );
```

Retrieve the values.

```
$('#target').val();
```

Manage only valid email address only.

```
$('#target').emailinput( { onlyValidValue: true ); // default: true
```

Manage only valid email address only.

```
$('#target').emailinput( { onlyValidValue: true ); // default: true
```

Change delimiters of retrieve the value.

```
$('#target').emailinput( { delim: ';' ); // default: ','
```

## `License`

emailaddressinput.js is available under the terms of the [MIT License](https://github.com/jongha/jquery-emailinput/blob/master/LICENSE).
