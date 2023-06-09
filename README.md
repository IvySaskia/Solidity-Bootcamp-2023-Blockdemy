<a name="readme-top"></a>



<!-- PROJECT LOGO -->

<br />
<div align="center">

![Solidit Bootcamp WE3 Latinas](https://us-ms.gr-cdn.com/getresponse-MzKFL/photos/ca6dca85-805a-4170-8e7c-a4f6bc3fe687.png)
  

<h3 align="center"><strong>DEMOCRATIZANDO PROYECTOS</strong></h3>

  <p align="center">
  This is the repository of the final project of <strong>Solidity Bootcamp of Blockdemy</strong> of <strong>2023</strong>
  
  A smart contract that allows voting on projects to be carried out in a community, giving the population the opportunity to vote for what they want and need in their community.
    <br />
    🔍 [Details of the project statment - Notion Site Blockdemy Project](https://blockde.me/guia-solidity-bootcamp)

🗂 [My presentation](https://www.canva.com/design/DAFkEA_MF-s/sP865HpRlXdARt0p6lqW5w/view?utm_content=DAFkEA_MF-s&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu)
    <br />
    <br />
    <a href="https://goerli.etherscan.io/address/0xB9Eb7227c839D3832cb8a2465666B1CF552954B3">View Smart Contract</a>
    ·
    <a href="https://github.com/IvySaskia/Solidity-Bootcamp-Blockdemy-Project/issues">Report Bug</a>
    ·
    <a href="https://github.com/IvySaskia/Solidity-Bootcamp-Blockdemy-Project/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#run-code">Run Code</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#team">Team</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->


## About The Project

Problem:

I realize that in LATAM countries, development proposals are approved or rejected depending on the party that proposes them, without really taking into account which proposal can considerably benefit citizens, which harms us and prevents economic and social growth. Additionally, I have noticed that votes in favor can sometimes be manipulated by keeping traditional records.


Solution:

I propose to carry out a voting system focused on the proposals without revealing the party that proposes it. I consider using blockchain technology against a traditional solution mainly due to 3 main factors:

1. I can ensure that voting is done only by the people who make up the chambers and only have the power to vote once
2. Ability to view voting records on the blockchain ensuring that the final result has not been tampered with.
3. Ability to guarantee that the vote will be focused on making the decision based on the value of the projects since the smart contract contains this rule.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* ![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
* ![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?logo=OpenZeppelin&logoColor=fff&style=for-the-badge)
* ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
* ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
* <a href='https://remix.ethereum.org/' target="_blank"><img alt='Ethereum' src='https://img.shields.io/badge/Remix.Ethereum-100000?style=for-the-badge&logo=Ethereum&logoColor=white&labelColor=222336&color=222336'/></a>
* <a href='https://metamask.io/' target="_blank"><img alt='.' src='https://img.shields.io/badge/Metamask-100000?style=for-the-badge&logo=.&logoColor=white&labelColor=FF7F08&color=FF7F08'/></a>
* <a href='https://etherscan.io/' target="_blank"><img alt='.' src='https://img.shields.io/badge/etherscan-100000?style=for-the-badge&logo=.&logoColor=white&labelColor=053883&color=053883'/></a>
* <a href='' target="_blank"><img alt='.' src='https://img.shields.io/badge/goerli.testnet-100000?style=for-the-badge&logo=.&logoColor=white&labelColor=0F65E4&color=0F65E4'/></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->

## Getting Started

There is 3 kinds of using this smart contact.
* Copy and paste code of **Ballot** Smart Contract on REMIX.Ethereum (This is the easiest way)
* Clone repo into REMIX.Ethereum (You need more configurations)
* Clone repository on locally machine (You need more configurations)

### Prerequisites

Open [REMIX.Ethereum](https://remix.ethereum.org/) 


### Run Code

1. Create a workspace.
2. Create a Ballot file.
3. Copy and paste code from allot file in repository to the Ballot file in Remix.
4. Press compiler.
5. Press deploy & run transactions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->

## Usage

0xB9Eb7227c839D3832cb8a2465666B1CF552954B3

Examples of list of projects: "Proyecto Escuela","Proyecto Hospital","Proyecto Cancha de futbol","Proyecto Cursos a jóvenes","Proyecto Apoyo a Madres solteras"
Max votes : 3

![image](https://user-images.githubusercontent.com/41027286/194960761-752e9e71-10ef-48f1-a115-e7b3fec0257a.png)

![image](https://user-images.githubusercontent.com/41027286/194960858-23721312-0dcf-4c8e-bedd-26dda5922b38.png)

![image](https://user-images.githubusercontent.com/41027286/194960818-3488e033-6bf9-4143-b323-16c91fbfecc1.png)

![image](https://user-images.githubusercontent.com/41027286/194960919-f653bd93-16e7-4ace-a06e-0180f6238e6c.png)

![image](https://user-images.githubusercontent.com/41027286/194961212-63c84c83-67de-48e9-ba1e-6299004716ed.png)



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [X] Add candidates
- [X] Add max votes
- [X] See list of candidates
- [X] Give right to vote to a voter
- [X] Vote
- [X] See winner project

See the [open issues](https://github.com/IvySaskia/Solidity-Bootcamp-Blockdemy-Project/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

* [Blockdemy](https://www.instagram.com/blockdemy)
* [Web3Latinas](https://www.instagram.com/web3latinas_)
* [Solidity Bootcamp]()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- TEAM -->
## Team

Made with 💜 by

👩🏽‍💻 **Ivy Saskia Sejas Rocabado**
- GitHub: [@IvySaskia](https://github.com/IvySaskia)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/IvySaskia/Solidity-Bootcamp-Blockdemy-Project.svg?style=for-the-badge
[contributors-url]: https://github.com/IvySaskia/Solidity-Bootcamp-Blockdemy-Project/graphs/contributors
