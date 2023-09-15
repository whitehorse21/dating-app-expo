## Dating App Like Tinder - Expo

4 screens are availables : Explore, Matches, Messages and Profile. You'll find some components like Card Component to pass props and variant. No frameworks UI like Bootstrap or Material UI are used.

- **Easy to use** 🤘
- **Made with Expo** ⚡
- **TypeScript supported** 🌞

## Installation and usage

Be sure, you have installed all dependencies and applications to run Expo project on your computer : [Getting Started with Expo](https://docs.expo.io/get-started/installation/).

This project works fine on iOS and Android.

### Running the project

Clone this repository :

```
git clone https://github.com/whitehorse21/dating-app-expo.git
cd tinder-expo
```

Install packages :

```
yarn
```

When installation is complete, run it :

```
yarn start
```

## Props

### CardItem

| Name          | Type    | Required | Description                                               | Example                                             |
| ------------- | ------- | -------- | --------------------------------------------------------- | --------------------------------------------------- |
| `image`       | string  | Yes      | Picture of member.                                        | `image="https://..."`                               |
| `name`        | string  | Yes      | Name of member.                                           | `name="John Doe"`                                   |
| `description` | string  | Yes      | Description of member.                                    | `description="Full-time Traveller. Globe Trotter."` |
| `matches`     | string  | Yes      | Match percentage.                                         | `matches="95"`                                      |
| `hasActions`  | boolean | No       | Display actions buttons (Like, Dislike, ...).             | `actions`                                           |
| `isOnline`    | string  | No       | Display online or offline badge (`Online` and `Offline`). | `status="Online"`                                   |
| `hasVariant`  | boolean | No       | Display another style of card (used for Matches screen).  | `variant`                                           |

### Message

| Name          | Type   | Required | Description             | Example                                                                                      |
| ------------- | ------ | -------- | ----------------------- | -------------------------------------------------------------------------------------------- |
| `image`       | string | Yes      | Picture of member.      | `image="https://..."`                                                                        |
| `name`        | string | Yes      | Name of member.         | `name="John Doe"`                                                                            |
| `lastMessage` | string | Yes      | Last message of member. | `lastMessage="You want order in Gotham. Batman must take off his mask and turn himself in."` |

### ProfileItem

| Name       | Type   | Required | Description                 | Example                                    |
| ---------- | ------ | -------- | --------------------------- | ------------------------------------------ |
| `name`     | string | Yes      | Name of member.             | `name="John Doe"`                          |
| `matches`  | string | Yes      | Match percentage.           | `matches="95"`                             |
| `age`      | string | No       | Age of member.              | `age="25"`                                 |
| `location` | string | No       | Location of member.         | `location="Paris, France"`                 |
| `info1`    | string | No       | More information of member. | `info1="Straight, Single"`                 |
| `info2`    | string | No       | More information of member. | `info2="Tea Totaller & Loves Photography"` |
| `info3`    | string | No       | More information of member. | `info3="Beaches, Mountain & Coffee"`       |
| `info4`    | string | No       | More information of member. | `info4="Last seen: 23h ago"`               |
