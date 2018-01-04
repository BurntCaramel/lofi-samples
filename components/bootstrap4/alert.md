# An alert, used for error, success, or informational messages


## classes:
- alert
- alert-{{ options.variation }}

> variation: success
### =
- alert
- alert-success


## primitive:
```jsx
<View class="{{ classes }}">{{ content }}</View>
```

> variation: danger
> ---
> Please enter a valid email address
### =
```jsx
<View class="alert alert-danger">Please enter a valid email address</View>
```


## html
```handlebars
<div class="{{ classes }}">{{ content }}</div>
```

> variation: danger
> ---
> Please enter a valid email address
### =
```handlebars
<div class="alert alert-danger">Please enter a valid email address</div>
```
