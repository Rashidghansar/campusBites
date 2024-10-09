

### Prerequisites

- Node
- Git
- MongoDB

### Installation

1. First of all, Clone this repository & navigate to the directory

```
git clone https://github.com/chiragverma11/EatEasy_Food_Ordering_Website.git
cd EatEasy_Food_Ordering_Website
```

2. Install the Dependencies

```
npm install
```

### Running Locally

- First Create `.env` file in root directory using the following content and make changes if required.

```
PORT=8080
MONGO_URI="YourMongoDBuri"
TOKEN_SECRET="JwtSecret"
```

- Starting the Server

```
npm start
```

or

```
npm run dev
```

### Adding Food Items to Database Collection (Menu)

To add food items to database run

```
npm run menu
```

Edit `items.csv` file under `assets/csv` to change food items.

