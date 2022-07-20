# Some title level 1

## Some title level 2 - 1

> Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

```javascript
// Sample context code
const planReducer = (state, action) => {
  switch (action.type) {
    case GET_PLANS:
      return {
        ...state,
        plans: action.payload,
        loading: false,
      }
    case ADD_PLAN:
      return {
        ...state,
        plans: [action.payload, ...state.plans],
        loading: false,
      }
    case UPDATE_PLAN:
      return {
        ...state,
        plans: state.plans.map((plan) =>
          plan._id === action.payload._id ? action.payload : plan
        ),
        loading: false,
      }
    case DELETE_PLAN:
      return {
        ...state,
        plans: state.plans.filter((plan) => plan._id !== action.payload),
        loading: false,
      }
    case CLEAR_PLANS:
      return {
        ...state,
        plans: [],
        filtered: null,
        error: null,
        current: null,
      }
    case SET_CURRENT:
      return {
        ...state,
        current: action.payload,
      }
    case CLEAR_CURRENT:
      return {
        ...state,
        current: null,
      }
    case PLAN_ERROR:
      return {
        ...state,
        error: action.payload,
      }
    default:
      return state
  }
}
```

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.
Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.
Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

## Some title level 2 - 2

> Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

```
yarn init
yarn install
yarn develop
```

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

## Some title level 2 - 3

> Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut magni tempore suscipit unde quidem vero sint autem culpa porro! Quae nihil obcaecati iusto? Vitae aperiam dicta corrupti in nobis officia itaque error unde! Quasi iste id numquam vitae dicta? Laudantium.
