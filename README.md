### Versions

Compiler: solc: 0.8.12+commit.f00d7308

Truffle: v5.5.2

Node: v14.17.0

### Quick Start

1.  cd into project repro

        cd E-Voting
        cd blockchain

2.  download node libraries

        npm install

3.  Download/Start ganache

https://truffleframework.com/ganache

4.  Compiling contracts

        truffle compile

5.  Migrating to ganache

_Note depending on ganache cli/ui you my need to change truffle.js port settings Current listing on port : 7545_

        truffle migrate --network development  --reset --all

6.  Testing on ganache

        truffle test

7.  Switch to FrontEnd & Testing

_Note Change settings to your Contract address to point to local_

          cd ..
          cd front-end
          npm install
          npm start

8.  Migrating to Rinkeby

_Note Change truffle settings to your Contract Creator address within the "from" rinkeby configuration_

        truffle migrate --network rinkeby  --reset --all

9.  Start FrontEnd on Rinkeby

_Note Revert back all your local configurations & configure it to point to rinkeby_

        npm start

### Test Voters

| User Name     | Aadhar Number | State          | Constituency | Age | isAlive |
| ------------- | ------------- | -------------- | ------------ | --- | ------- |
| Suresh        | 482253918244  | Andhra Pradesh | Guntur       | 21  | ✅      |
| Ramesh        | 532122269467  | Andhra Pradesh | Guntur       | 37  | ❌      |
| Mahesh        | 468065932286  | Andhra Pradesh | Guntur       | 26  | ✅      |
| Krishna       | 809961147437  | Andhra Pradesh | Krishna      | 19  | ✅      |
| Narendra      | 908623597782  | Andhra Pradesh | Krishna      | 36  | ✅      |
| Raghu         | 760344621247  | Andhra Pradesh | Krishna      | 42  | ✅      |
|               |               |                |              |     |         |
| Pushkar Kumar | 908704156902  | Bihar          | Patna        | 25  | ✅      |
| Kunal Kumar   | 778925466180  | Bihar          | Patna        | 37  | ✅      |
| Aausi         | 756623869645  | Bihar          | Patna        | 85  | ❌      |
| Ruchika       | 967746320661  | Bihar          | Patna        | 26  | ✅      |
| Rambabu       | 727938171119  | Bihar          | Patna        | 17  | ✅      |
| Matajii       | 609015917688  | Bihar          | Patna        | 98  | ✅      |
| Kumar Sanket  | 393071790055  | Bihar          | Dehri        | 29  | ✅      |
| Pratik        | 983881786161  | Bihar          | Dehri        | 40  | ✅      |
| Pratiba       | 588109459505  | Bihar          | Dehri        | 68  | ❌      |
| Mamata        | 620107691388  | Bihar          | Dehri        | 63  | ❌      |
| Ravi Varma    | 403561319377  | Bihar          | Dehri        | 42  | ✅      |
| Rahul         | 837970229674  | Bihar          | Dehri        | 56  | ✅      |

### Politicians who participate in elections

| Candidate Name     | Party Name | State          | Constituency |
| ------------------ | ---------- | -------------- | ------------ |
| Chandra Babu Naidu | TDP        | Andhra Pradesh | Guntur       |
| Jagan Mohan Reddy  | YSRCP      | Andhra Pradesh | Guntur       |
| G V Anjaneyulu     | TDP        | Andhra Pradesh | Krishna      |
| Anil Kumar Yadav   | YSRCP      | Andhra Pradesh | Krishna      |
|                    |            |                |              |
| Narendra Modi      | BJP        | Bihar          | Patna        |
| Rahul Gandhi       | INC        | Bihar          | Patna        |
| Tejaswi Yadav      | RJD        | Bihar          | Patna        |
| Arvind Kejriwal    | AAP        | Bihar          | Patna        |
| Mamata Banarjee    | TMC        | Bihar          | Patna        |
| Jyoti Basu         | CPIM       | Bihar          | Patna        |
| Amit Shah          | BJP        | Bihar          | Dehri        |
| Priyanka Gandhi    | INC        | Bihar          | Dehri        |
| Lalu Yadav         | RJD        | Bihar          | Dehri        |
| Manish Sisodia     | AAP        | Bihar          | Dehri        |
| Prakash Karat      | CPIM       | Bihar          | Dehri        |

## Sample Images

<img src="https://github.com/GeekyAnts/sample-e-voting-system-ethereum/blob/main/sample-images/1.png?raw=true"><br>
<img src="https://github.com/GeekyAnts/sample-e-voting-system-ethereum/blob/main/sample-images/2.png?raw=true"><br>
<img src="https://github.com/GeekyAnts/sample-e-voting-system-ethereum/blob/main/sample-images/3.png?raw=true"><br>
<img src="https://github.com/GeekyAnts/sample-e-voting-system-ethereum/blob/main/sample-images/4.png?raw=true"><br>
# sample-e-voting-system
