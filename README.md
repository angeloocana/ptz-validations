# ptz-validations

[![Build Status](https://travis-ci.org/polutz/ptz-validations.svg)](https://travis-ci.org/polutz/ptz-validations)
[![NPM](https://img.shields.io/npm/v/ptz-validations.svg)](https://www.npmjs.com/package/ptz-validations)
[![codecov.io](http://codecov.io/github/polutz/ptz-validations/coverage.svg)](http://codecov.io/github/polutz/ptz-validations)
[![Dependency Status](https://gemnasium.com/polutz/ptz-validations.svg)](https://gemnasium.com/polutz/ptz-validations)
[![bitHound Score](https://www.bithound.io/github/gotwarlost/istanbul/badges/score.svg)](https://www.bithound.io/github/polutz/ptz-validations)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

## Translations
[pt-br](https://github.com/polutz/ptz-validations/blob/master/README.pt-br.md)
[en-us](https://github.com/polutz/ptz-validations/blob/master/README.md)

Validate your js objects.


## Use

### Install
```
    npm install --save ptz-validations
```

### How to use

#### E-mail Validation
```
    import { validateEmail } from 'ptz-validations';

    validateEmail('angeloocana@gmail.com'); // Return TRUE

    validateEmail('angeloocana_gmail_com'); // Return FALSE

```




## Contribute

### NPM Global packages
```
    npm install -g ts-node babel-cli
```

### Setup
```
    npm install   
```

### Test
```
    npm test
```
