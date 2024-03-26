# ICP Development Environment with Azle and React

### Locally:

When the editor opened, run the following commands to deploy the canisters and start a development server:

```sh
npm install 
dfx deploy # Deploy canisters locally

npm start # Start the development server
```

The frontend will update automatically as you save changes. 
For the backend, run `dfx deploy backend` to redeploy.
To redeploy all canisters (front- and backend), run `dfx deploy`.

When ready, run `dfx deploy --network ic` to deploy your application to the ICP mainnet.

## Testing

To test we recommend to use Postman. 

## 🛠️ Technology Stack

- React
- Vite
- Typescript
- Azle