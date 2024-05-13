# Trustee Smart-contracts practice

## Solidity

#### Матеріали
1. [Solidity doc](http://solidity.readthedocs.io/en/develop/)
2. [Рекомендації щодо оформлення коду Solidity](http://solidity.readthedocs.io/en/develop/style-guide.html)
3. [Розповсюджені шаблони та підходи для написання смарт-контрактів](http://solidity.readthedocs.io/en/develop/common-patterns.html)
4. [Cryptozombies](https://cryptozombies.io/)

#### Задачі
1. Матеріали для ознайомлення `(1-2 дні)`:
   - [Поняття смарт-контракт](https://forklog.com/chto-takoe-smart-kontrakt/);
   - [Вступ до розробки смарт-контрактів Ethereum](https://habrahabr.ru/post/335710/);
   - [Розробка смарт-контрактів на Solidity](https://habrahabr.ru/post/312008/).
2. Написати свій найпростіший ERC-20 токен (скомпілювати в Remix або Truffle, закинути в будь-який TestNet, надати посилання на контракт, показати тестові транзакції з переказу токенів між декількома (мінімум 3) адресами. Переказ токенів можна здійснити за допомогою MyEther Wallet. Дослідити транзакцію в Etherscan: розібратись за що відповідає кожен з параметрів, які показані в Etherscan. `(1 день)`
   Матеріали зі створення та запуску токенів:
   - [Створення та запуск токенів](https://medium.com/bitfwd/how-to-issue-your-own-token-on-ethereum-in-less-than-20-minutes-ac1f8f022793);
   - [Фундамент](https://www.ethereum.org/token).

     Необхідні для виконання завдання матеріали і сервіси:
   - [ERC-20 token standard](https://medium.com/blockchannel/the-anatomy-of-erc20-c9e5c5ff1d02);
   - [Remix](https://remix.ethereum.org/);
   - [Truffle github](https://github.com/trufflesuite/truffle/);
   - [MyEtherWallet](https://www.myetherwallet.com/);
   - [MetaMask](https://metamask.io/);
   - [Etherscan](https://etherscan.io/);
3. Опублікувати вихідний код контракту в TestNet `(1 день)`.
4. Дослідити контракт [токена Edgeless](https://etherscan.io/token/Edgeless) і розібратися чим він відрізнятися від стандартного ERC-20 токена. `(1 день)`.
   - [код контракту на Solidity](https://github.com/EdgelessCasino/Smart-Contracts);
5. Написати свій ERC-20 токен з можливістю спалювання певної кількості токенів після певної дати (закинути на TestNet, надати посилання на контракт, показати тестові транзакції з переказу токенів між декількома (мінімум 3) адресами. `(1 день)`.
6. Написати ERC-20 токен з двома власниками (додатково реалізувати можливість додавати власників за згодою більше половини поточних власників). `(1-2 дні)`.
7. Додати в ERC-20 токен функціональність виплати дивідендів в ETH, при надходженні ETH на баланс контракту. Дивіденди розподіляти пропорційно кількості токенів `(1-2 дні)`.
   - [Iterable Mapping pattern](https://github.com/ethereum/dapp-bin/blob/master/library/iterable_mapping.sol);
   - [Смарт-контракти Ethereum: структуруємо токени як акції](https://habrahabr.ru/post/328246/);
   - [Альтернативна бібліотека для Iterable Mapping](https://github.com/szerintedmi/solidity-itMapsLib).
8. Написати контракт, котрий розподіляє ERC-20 токени описані іншим контрактом (додатково реалізувати функцію додаткової емісії цих же токенів) `(1-2 дні)`.
   - [Приклад](https://stermi.medium.com/how-to-create-an-erc20-token-and-a-solidity-vendor-contract-to-sell-buy-your-own-token-8882808dd905);
10. Написати контракт MultiSig, котрий реалізує функцію голосування за роздачу токенів на певну адресу з певною сумою `(1-2 дні)`.
   Умови:
   - Видавати токени на адресу тільки після того, як кількість тих, хто проголосував “ЗА” більше, ніж половина.
   - Реалізувати властивість контракту, що дозволить повторно голосувати за роздачу токенів на одну і ту ж адресу.
   - Контракт повинен враховувати, що кількість адрес, котрі голосують може бути парною чи непарною.

## Web3.js (Node.JS lib)
[Web3 doc](https://web3js.org/)

1. Навчитися визначати баланс ETH на заданій адресі `(1 день)`.
2. Навчитися передавати ETH програмно `(1 день)`.
3. Реалізувати можливість деплойменту контракту з початковими параметрами переданими в конструктор `(1 день)`.
4. Реалізувати простий скрипт розподілення ERC-20 токенів від імені власника (на вході масив з адресами і кількістю токенів для кожної адреси) `(1-2 дні)`.
5. Написати скрипт визначення балансу ERC-20 токенів заданого контракту на адресі (списку адрес) `(1-2 дні)`.
