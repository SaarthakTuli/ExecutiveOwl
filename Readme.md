# ExecutiveOwl

A <b>Full Stack Finance Management Web App using <a href="https://react.dev/">React JS<img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" alt="reactjs" width="40" height="40" /></a>, <a href="https://www.mongodb.com/docs/"> MongoDB <img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original.svg" alt="mongodb" width="24" height="24" /></a></b> . The server is created using <b><a href="https://nodejs.org/en/docs">NodeJS<img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" width="40" height="40" /></a> and <a href="https://expressjs.com/">ExpressJS<img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original.svg" width="40" height="40" /></a></b>, the frontend API manament is handled using <b><a href="https://redux.js.org/">Redux<img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" alt="redux" width="40" height="40" /></a></b>. It is <b>Fully Responsive</b> and it uses <b>Linear Regression</b> to predict future revenue.

## Deployment

Demo data required to add to you database has been added inside `/server/data/data.js`

You can start the server using

```bash
cd server
npm run dev
```

Output when the server starts

```
Server Port 1337
```

and to start the React App we run:-

```bash
cd client
npm run dev
```

We will need 2 environment files first:

- Server Directory `.env` file

```code
MONGO_URL=XXXXXXXXXXXX
PORT=1337
```

- Client Directory `.env.local` file

```code
VITE_BASE_URL=http://localhost:1337/
```

## Showcase

The Website is live at :-

https://executive-owl.vercel.app/

## Preview

![Screenshot 2023-10-28 at 12 08 45 AM](https://github.com/SaarthakTuli/ExecutiveOwl/assets/89101837/a420429d-50ad-49d4-bfb2-1e20711b34b4)

![Screenshot 2023-10-28 at 12 08 57 AM](https://github.com/SaarthakTuli/ExecutiveOwl/assets/89101837/6e881176-6b00-48a6-b6d9-342b7d2155a4)


