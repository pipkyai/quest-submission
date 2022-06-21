# quest-submission by Doki-dok

## chapter 1 day 1

LFG!!!!

1.Blockchain is a decentralized ledger that everyone can view and make their own records there. These records go into blocks from which the chain is made up. There is no single server so important data is stored on multiple machines.

2.A smart contract is a small program whose source code is written in the blockchain. It performs the functions described by the creator, as a rule, it works with data.

3.The script is an operation to request data from a smart contract or "read" the blockchain, it's free. A transaction is an entry into the blockchain of data according to the rules described in the smart contract, it costs "gas".



## chapter 1 day 2

1.Safe - because of the structure of the language<br/>
  Clarity - easy to read language <br/>
  Approachability - easy to write language <br/>
  Developer Experience - easy to track errors in the code<br/>
  Resource Oriented Programming - resources are what we will need to work with.<br/>


2.This is a language specially created for smart contracts. The laconically constructed structure makes it easy to audit the code. Which increases the security and clarity of the code. The language is designed in such a way, that you can easily to learn to write the code not only with experience but also without programming skills. Cadence is resource-oriented, which makes it unique and helps a lot in working with blockchain.



## chapter 2 day 1

1. 
<img width="1166" alt="2 1 1" src="https://user-images.githubusercontent.com/68229318/172945673-e4f17fe6-dafe-4e6f-83f6-a1662ef25df0.png">
2.
<img width="1173" alt="2 1 2" src="https://user-images.githubusercontent.com/68229318/172946314-8a1d2b72-adae-4b8d-91b7-ec2e6fd881b4.png">


## chapter 2 day 2
1. We can't call the "changeGreeting" function because it writes(!) data to the contract.
2. To start a transaction, you will need to perform authorization (For example in Blocto)
3. With the "prepare" function there is access to the information/data in my account. With "execute" function we can change data on blockchain. The "prepare" function also can change data on blockchain, but for the cleanliness of the code, it is not recommended.
4. Contract
 <img width="1156" alt="2 2 1" src="https://user-images.githubusercontent.com/68229318/172954537-7b232ed2-e300-4c2d-8af8-deb9fb731e76.png">
Script
<img width="1159" alt="2 2 2" src="https://user-images.githubusercontent.com/68229318/172954603-63df644d-e2be-4e47-96da-239b9b34ee9c.png">
Transaction
<img width="1158" alt="2 2 3" src="https://user-images.githubusercontent.com/68229318/172954645-8402e00d-2682-4fb4-add0-b9e88083d6e8.png">
Done!
<img width="395" alt="2 2 4" src="https://user-images.githubusercontent.com/68229318/172954713-f2708409-c2cc-4455-af69-2ff27ed69cb1.png">


## chapter 2 day 3
1.Array with favourte people.
<img width="1150" alt="1" src="https://user-images.githubusercontent.com/68229318/173402867-62369892-7980-4932-af43-2ce7cab7e887.png">
2.My favourite apps rating.
<img width="1158" alt="2" src="https://user-images.githubusercontent.com/68229318/173403120-2eb31a51-cc02-4b5e-b49a-327ae7c0d24c.png">
3.The (!) operator warns us that one of the required values does not contain the data necessary for the further operation of the program.

4.The error indicates that the type of data we expect to receive does not match the one being sent. We got this error because we didn't warn the compiler about it. We can fix this error by adding (!) or (?) operators:

<img width="681" alt="Снимок экрана 2022-06-13 в 20 14 31" src="https://user-images.githubusercontent.com/68229318/173408698-25d048e7-13d2-4660-83f6-feb01224fd5e.png">

<img width="747" alt="Снимок экрана 2022-06-13 в 20 15 12" src="https://user-images.githubusercontent.com/68229318/173408746-f926252c-0695-4d6c-917a-9277426b5e85.png">

## chapter 2 day 4
1.Deploying contract full of monsters
<img width="1146" alt="Снимок экрана 2022-06-14 в 15 51 29" src="https://user-images.githubusercontent.com/68229318/173581374-16591acf-71d1-4b12-b95c-8bd4969af192.png">
2.Create a dictionary with our monsters

<img width="316" alt="Снимок экрана 2022-06-14 в 15 37 06" src="https://user-images.githubusercontent.com/68229318/173578900-6bece45d-55c3-47c7-8b9d-00c55e722958.png">

<img width="223" alt="Снимок экрана 2022-06-14 в 15 37 27" src="https://user-images.githubusercontent.com/68229318/173578913-3e8e5c7d-18f7-493a-966a-a1cd2364b597.png">

3. Create a function for addiing new monsters


<img width="1064" alt="Снимок экрана 2022-06-14 в 15 46 21" src="https://user-images.githubusercontent.com/68229318/173580485-c9b45dde-4fc8-4c78-9954-79a7df61c77e.png">

4.Make a transaction and create a monster for each account
<img width="1134" alt="Снимок экрана 2022-06-14 в 16 03 44" src="https://user-images.githubusercontent.com/68229318/173584396-1021923e-94bd-4665-b550-16b9a8e68fdf.png">

5. Let's take a look at the monsters that users have created
<img width="1152" alt="Снимок экрана 2022-06-14 в 16 19 15" src="https://user-images.githubusercontent.com/68229318/173587308-46394cf6-f6c6-47c5-9685-8242763af31a.png">


## chapter 3 day 1

1.Resources are more secure in general than structs because : 
  they cannot be copied, 
  they cannot be lost, 
  they cannot be changed.

2.If we want to create a onFlow NFT, it is better to use resources for storing NFT's data.

3.If we want to make new Resource we need to use "create" keyword.

4.We can't craete a Resource with scripts or transactions, because it is outside(!) the Contract.

5.@Jacob

6.<img width="1102" alt="Снимок экрана 2022-06-21 в 17 15 20" src="https://user-images.githubusercontent.com/68229318/174822293-399929c5-770e-45eb-af77-e8ab9170c317.png">
