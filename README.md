<p align="center">
<img src="https://pigjian.com/images/v-distpicker.png" alt="Powered By Jiajian Chan" width="160">
</p>

<p align="center">A flexible, highly available district selector for picking provinces, cities and districts of China.</p>

# V - Distpicker

Here is [documents](http://distpicker.pigjian.com/)

## Installation

```javascript
npm install v-distpicker-stzhang --save
```

Or

```javascript
yarn add v-distpicker-stzhang --save
```

## Usage

**Register component**

Registe global component:

```javascript
import Distpicker from 'v-distpicker-stzhang'

Vue.component('v-distpicker', Distpicker)
```

Registe component:

```javascript
import VDistpicker from 'v-distpicker-stzhang'

export default {
  components: { VDistpicker }
}
```

**How to use**

Basic:

```javascript
<v-distpicker />
```

Default Value:

```javascript
<v-distpicker province="广东省" city="广州市" area="海珠区" />
```

Mobile:

```javascript
<v-distpicker type="mobile" />
```

## Contributors

- [Jiajian Chan](http://github.com/jcc)

## Thanks

- [Distpicker](https://github.com/fengyuanchen/distpicker)

## License

The plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
