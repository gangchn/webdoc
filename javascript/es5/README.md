# WebDoc Javascript For ECMAScript 2009

This is Javascript for ECMAScript 2009(ES5) standard chapter entry, you can start read from here.

- [Variable naming](#Variable-naming)
- [Constant naming](#Constant-naming)
- [Enumeration naming](#Enumeration-naming)

<a name="Variable-naming"></a>

### # Variable naming

**Always using lowerCamelCase to naming your variable.**

Bad

```
var MYCARD = 'red car'

var my-posts = ['Hello webdoc']
```

Good

```
var myCard = 'red car'

var myPosts = ['Hello webdoc']
```

<a name="Constant-naming"></a>

### # Constant naming

**For constant, using SCREAMING_SNAKE_CASE to naming it.**

Bad

```
const MinNumber = 0

const maxNumber = 10
```

Good

```
const MIN_NUMBER = 0

const MAX_NUMBER = 10
```

<a name="Enumeration-naming"></a>

### # Enumeration naming

**It is best experience for using PascalCase to naming enumeration.**

Bad

```
const NATURE_WEEK = {
  SUNDAY: 'SUNDAY',
  MONDAY: 'MONDAY',
  TUESDAY: 'TUESDAY',
  WEDNESDAY: 'WEDNESDAY',
  THURSDAY: 'THURSDAY',
  FRIDAY: 'FRIDAY',
  SATURDAY: 'SATURDAY'
}
```

Good

```
const NatureWeek = {
  SUNDAY: 'SUNDAY',
  MONDAY: 'MONDAY',
  TUESDAY: 'TUESDAY',
  WEDNESDAY: 'WEDNESDAY',
  THURSDAY: 'THURSDAY',
  FRIDAY: 'FRIDAY',
  SATURDAY: 'SATURDAY'
}
```
