Source

Install the proper version of node otherwise there 
will be nasty errors 
yelling `ERR_OSSL_EVP_UNSUPPORTED`.


    $ nvm install lts/erbium


### 3.1 Use reducers to manage complex state
This makes the state transition decoupled from
the component and testable. 

### 3.6 Manage __global__ state with redux
Use `createStore` to create a global state storage and 
pass down to the children via a `Provider`. 
The state is accessed via `useSelector` and 
the `useDispatch` hook returns a function to 
send the actions to the data store.
