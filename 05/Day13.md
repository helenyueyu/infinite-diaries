Successfully created a custom route today! It was related to my **search** and **pagination** feature. This is my custom route in my `questions_controller.rb`: 

```js
get 'banana(search/:search)', to: 'questions#search', search: /.*/
```
