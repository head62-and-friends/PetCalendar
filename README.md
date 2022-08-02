# PetCalendar

A calendar application that refreshes you with cute pet images.

<img src="./docs/demo.gif" alt="pet-calendar-demo" width="800px">

## Run the APP

### Step 1: Unsplash API credential

To run the app on your local machine, you will first need to have an Unsplash API credential.
Go to the [Unsplash Image API](https://unsplash.com/developers) page and create a new Application.
Save the `Access Key` and the `Application Name`:

<img src="./docs/unsplash.png" alt="unsplash api" width="700px">

### Step 2: Create .env.development file

Create `pet-calendar/.env.development` file. Follow the format of (`pet-calendar/.env.development`)[https://github.com/niuniuanran/PetCalendar/blob/develop/pet-calendar/env.example] and paste the strings from Step 1 into it.

### Step 3: Run the Application

Run the following steps to start the application:

```
$ cd pet-calendar
$ npm install
$ npm run start
```

Now enjoy your pet calendar at http://localhost:3000/.
