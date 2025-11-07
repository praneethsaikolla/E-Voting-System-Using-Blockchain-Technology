# BlockChainVoting

A blockchain-based E-voting system, created as the final year project. Developed by Praneeth Sai Kolla, Sri Ram Sai Guruju, Deepak Yenduri, and Amarnath Devarasetty.

> The application is MIT-Licensed.

## Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:3000
npm start
```

Create your own `.env` file and the file should contain:

```
EMAIL=YOUR_EMAIL_ID
PASSWORD=YOUR_PASSWORD_FOR_EMAIL_ID
```

Install MetaMask extension (https://metamask.io/download.html) and make sure to have some Ether to test the application locally. Ether can be fetched from Rinkeby Faucet (https://faucet.rinkeby.io/)

#### Note:

- Make sure to install Node.js v11.14.0 to make sure the app runs fine. Testing for other node versions is yet to be done.
- MongoDB must be working in background on localhost:27017

###### Please star the repo if it helped you in any way!

## Tech Stack:

- Solidity/Web3 (for writing/connecting the Blockchain contract)
- Next.js & Semantic UI React (front-end)
- MongoDB/ExpressJS/Node.js (back-end)
- IPFS (file storage for images)

## Screenshots of the app:

### Homepage of the application:
![Homepage](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/homepage.PNG)

### Company registers/logs in:
![Company Login](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/company_login.PNG)

### Company creates an election if not created:
![Create Election](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/create_election.PNG)

### Dashboard on successful election creation:
![Dashboard](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/dashboard.PNG)

### List of candidates for the election (here, you can add candidates):
![Candidate List](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/candidate_list.PNG)

### Candidate has been notified on the mail:
![Candidate Mail](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/candidate_registeration_mail.PNG)

### List of voters for the election (here, you can add voters):
![Voter List](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/voterlist.PNG)

### Voters have been sent their secure usernames and passwords on the mail:
![Voter Mail](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/voter_registeration_mail.PNG)

### Voter login page:
![Voter Login](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/voter_login.PNG)

### Successful voting scenario:
![Successful Voting](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/successful_voting.PNG)

### Unsuccessful voting scenario:
![Unsuccessful Voting](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/unsuccessful_voting.PNG)

### Notification to each candidate and voter for the winner of candidates:
![Winner Notification](https://github.com/praneethsaikolla/E-Voting-System-Using-Blockchain-Technology/blob/main/screenshots/winner_candidate_mail.PNG)

## Authors

- **Praneeth Sai Kolla**
- **Sri Ram Sai Guruju**
- **Deepak Yenduri**
- **Amarnath Devarasetty**

## License

This project is licensed under the MIT License - see the LICENSE file for details.
