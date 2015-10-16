#Fundera Redux Snippets

## Usage

 - create action ('rfact')
```js
export const $1 = "$1";
function $2($3) {
	return { type: $1, $3 };
}
```
 - create async action ('rfaact')
```js
export function $1() {
	return function (dispatch) {
	    ApiUtil.$2()
        .then( (res) => {
	        dispatch($3(res);
         });
    };
}
```

 - reducer ('rfred')
```js
function $1 ( state = [], action ) {
	switch(action.type) {

    default:
	    return state;
    }
}
```

- reducer action ('rfredact')
```js
 case types.$1:
	 return ;
```

- dispatch action ('rfdact')
```js
 on$1={ $2 => dispatch(actions.$3.$1($2)}
```
