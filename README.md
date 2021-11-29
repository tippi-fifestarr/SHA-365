# SHA-365
[our specifications](https://docs.google.com/document/d/1htsIUW1AiagQT3W35X_A3B6HL4_4zS1a8a8oWTU7og8/edit#heading=h.lgowqagkisla)

[devpost link](https://devpost.com/software/sidechain-hackathon-activities-356-sha365)

[the script for the video](https://docs.google.com/document/d/1RC5u1Vcx47oigiNUMLDc4cKQpS-qPH3qCqTe81cy1JA/edit?usp=sharing)

## Working pages for SHA-365
1. Hexhub2 collection of links (step by step) https://github.com/tippi-fifestarr/hexhub2/tree/master
![image](https://user-images.githubusercontent.com/62179036/143809708-939265b4-ca11-4506-b686-d6098bb5b7ed.png)

2. [Registration page](https://github.com/tippi-fifestarr/ChainlinkTeamFun/tree/master) & https://upbeat-albattani-f30fb4.netlify.app/
![image](https://user-images.githubusercontent.com/62179036/143809761-e9105e78-1711-41a8-a9e1-da2120a3687e.png)

3. Missions page https://github.com/tippi-fifestarr/ethereum-boilerplate/tree/main
![image](https://user-images.githubusercontent.com/62179036/143810232-a2626f47-b7b6-4fa6-829b-2fe2d31fd901.png)

4. [Harmony Testnet Aragon DAO](client.aragon.org/) SHA365.eth how to: https://youtu.be/dKTkWrT5eDs

## [Summary of contracts & chainlink features](https://github.com/tippi-fifestarr/ChainlinkTeamFun)

> click above for original repo

# MVP smart contracts

[TeamLinkChums.sol](https://github.com/tippi-fifestarr/ChainlinkTeamFun/blob/main/TeamLinkChums.sol) => the newest version, upgraded from ![image](https://user-images.githubusercontent.com/62179036/143808739-f8e33aa0-1dd0-4b23-a479-9c25cb3cb5aa.png)
this we uploaded but couldn't successfully verify the contract, HOWEVER https://kovan.etherscan.io/address/0x6db5938866d95cf496fc632bd7df956c7e241186#events it was successfully emitting an event each time Keepers updated the Day. https://keepers.chain.link/kovan/1707

[mintCardTwoTeams](https://github.com/tippi-fifestarr/ChainlinkTeamFun/blob/main/mintCardTwoTeams.sol) => this uses Chainlink VRF to randomly assign minters to one of two teams ([red card](https://rinkeby.rarible.com/token/0x6ede7F3c26975AAd32a475e1021D8F6F39c89d82:84799889509624640499281787148111605021253889930053214964227142096833187151893?tab=details) or [blue card](https://rinkeby.rarible.com/token/0x6ede7F3c26975AAd32a475e1021D8F6F39c89d82:84799889509624640499281787148111605021253889930053214964227142096833187151894?tab=details)) https://kovan.etherscan.io/address/0x8a6eB8BFf35f9dAD098dfe1Ad8F5EEed277F03B7#code

## design and more!

![image](https://user-images.githubusercontent.com/62179036/143810385-acd38bba-216d-4dd4-adee-746408db27cb.png)
