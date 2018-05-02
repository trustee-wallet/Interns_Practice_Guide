# BlockSoftLab Smart-contracts practice

## Solidity
[(http://solidity.readthedocs.io/en/develop/)](http://solidity.readthedocs.io/en/develop/)

1. Материалы для ознакомления `(1-2 дня)`:
   - [Понятие смарт-контракта](https://forklog.com/chto-takoe-smart-kontrakt/);
   - [Начало разработки на Ethereum](https://habrahabr.ru/post/336132/);
   - [Введение в разработку умных контрактов Ethereum](https://habrahabr.ru/post/335710/);
   - [Разработка умных контрактов на Solidity](https://habrahabr.ru/post/312008/).
2. Написать свой самый простой ERC-20 токен (скомпилировать в truffle, закинуть на Ropsten TestNet, предоставить ссылку на контракт, код проекта на GitHub и показать тестовые транзакции по переводу токенов между несколькими (минимум 3) адресами.
   Перевод токенов можно осуществить с помощью MyEtherWallet. `(4 дня)`
   Научиться основам Solidity - пройти [урок1](https://cryptozombies.io/en/lesson/1) и [урок2](https://cryptozombies.io/en/lesson/2) на пути создания криптозомби
   Материалы по созданию и запуску токенов:
   - [Создание и запуск токенов - быстро и весело](https://medium.com/bitfwd/how-to-issue-your-own-token-on-ethereum-in-less-than-20-minutes-ac1f8f022793);
   - [А теперь - фундаментально и качественно](https://www.ethereum.org/token).

     Необходимые для выполнения задания материалы и сервисы:
   - [ERC-20 token standard](https://theethereum.wiki/w/index.php/ERC20_Token_Standard);
   - [Truffle docs](http://truffle.readthedocs.io/en/beta/);
   - [Truffle github](https://github.com/trufflesuite/truffle/);
   - [Ropsten Testnet](https://ropsten.etherscan.io/);
   - [MyEtherWallet](https://www.myetherwallet.com/);
   - [MetaMask](www.metamask.io);
   - [GitHub](https://github.com/) и [Git](https://git-scm.com/docs)
3. Опубликовать исходный код контракта в Ropsten TestNet `(1 день)`.
4. Изучить контракт [токена Edgeless](https://etherscan.io/token/Edgeless) и разобраться чем он отличается от стандартного ERC20 токена `(1 день)`.
   - [Edgeless Whitepaper](https://coss.io/documents/white-papers/edgeless.pdf);
   - [код контракта на Solidity](https://github.com/EdgelessCasino/Smart-Contracts).
5. Завершить [урок3](https://cryptozombies.io/en/lesson/3) по созданию криптозомби. Написать свой ERC-20 токен с возможность сжигания определенного количества токенов после определенной даты (скомпилировать в truffle, закинуть на Ropsten TestNet, предоставить ссылку на контракт, код проекта на GitHub и показать тестовые транзакции по переводу токенов между несколькими (минимум 3) адресами `(1 день)`.
6. Написать ERC-20 токен с двумя владельцами (дополнительно реализовать возможность добавлять владельцев при согласии больше половины текущих владельцев) `(1-2 дня)`.
7. Добавить в ERC-20 токен функционал выплаты дивидендов в ETH, при поступлении ETH на баланс контракта токена. Дивиденды распределять пропорционально количеству токенов `(3 дня)`.
   - [Iterable Mapping pattern](https://github.com/ethereum/dapp-bin/blob/master/library/iterable_mapping.sol);
   - [Смарт контракты Ethereum: структурируем токены как акции](https://habrahabr.ru/post/328246/);
   - [Альтернативная библиотека для Iterable Mapping](https://github.com/szerintedmi/solidity-itMapsLib).
8. Написать контракт, который распределяет ERC20 токены описанные другим контрактом (дополнительно реализовать функцию дополнительной эмиссии этих же токенов) `(1-2 дня)`.
9. Написать контракт MultiSig, который реализует функцию голосования за раздачу токенов на определенный адрес с определенной суммой `(2 дня)`.
   Условия:
   - Выдавать токены на адрес только после того, как количество проголосовавших “ЗА” больше, чем половина.
   - Реализовать свойство контракта которое позволит повторно голосовать за раздачу токенов на один и тот же адрес.
   - Контракт должен учитывать, что количество адресов, которые голосуют может быть четным и нечетным.
10. Завершить [урок 4](https://cryptozombies.io/en/lesson/4) и [урок 5](https://cryptozombies.io/en/lesson/5) по созданию криптозомби `(1-2 дня)`.

#### Дополнительные материалы
1. [Рекомендации по оформлению кода на Solidity](http://solidity.readthedocs.io/en/develop/style-guide.html)
2. [Распространенные шаблоны и подходы при написании смарт-контрактов](http://solidity.readthedocs.io/en/develop/common-patterns.html)

## Web3.js (Node.JS lib)
[(http://web3js.readthedocs.io/en/1.0/index.html)](http://web3js.readthedocs.io/en/1.0/index.html)

1. Завершить [урок 6](https://cryptozombies.io/en/lesson/6) по взаимодействию с криптозомби через web3.
2. Научиться определять баланс ETH на заданном адресе `(1 день)`.
3. Научиться передавать ETH программно `(1 день)`.
4. Реализовать возможность деплоймента контракта с начальными параметрами переданными в конструктор `(1 день)`.
5. Реализовать простой скрипт распределения ERC20 токенов от имени владельца (на входе массив с адресами и количеством токенов для каждого адреса) `(1-2 дня)`.
6. Написать скрипт определения баланса ERC20 токенов заданного контракта на адресе (списке адресов) `(1-2 дня)`.


## Web3.js (client lib)
[(https://github.com/ethereum/wiki/wiki/JavaScript-API)](https://github.com/ethereum/wiki/wiki/JavaScript-API)

1. Подключить, настроить и попробовать подключиться к Ropsten Testnet `(3 дня)`
   - [Client web3.js](https://github.com/ethereum/web3.js/);
   - [Ropsten Testnet](https://ropsten.etherscan.io/);
   - [Infura service](https://infura.io/) (тут нужно получить API ключь для удаленного подключения к сети Ethereum).
2. Разобраться с проектом - примером Ethereum Pet Shop. По возможности переключить его на работу с Ropsten Testnet через infura.io `(1 день)`
3. ...


## Smart-contracts security

[Атаки на умные контракты Ethereum](https://www.cryptologie.net/article/423/attacks-on-ethereum-smart-contracts/)


## Truffle test

1. Научиться писать тесты на JavaScript для смарт контрактов `(1-2 дня)`.
   Полезные материалы:
   - [Truffle testing your contract](http://truffleframework.com/docs/getting_started/testing);
   - [Writing tests in JavaScript](http://truffleframework.com/docs/getting_started/javascript-tests);
   - [Автоматические тесты при помощи chai и mocha](https://learn.javascript.ru/testing).
2. Воспроизвести [эти тесты](http://truffleframework.com/docs/getting_started/javascript-tests) `(1 день)`.
3. Написать тесты для ERC20 токена без параметров в конструкторе `(1 день)`:
   - Проверить является ли контракт совместим с ERC20 стандартом;
   - Написать тесты для каждой функции;
   - Сделать проверку для всех публичных переменных.
4. Написать тест для контракта, в котором при деплойменте контракта задаються параметры в конструктор `(1-2 дня)`.


## Atomic Swap
1. Ознакомиться `(1 день)`:
   - [Atomic Swaps](https://bitcointechtalk.com/atomic-swaps-d6ca26b680fe);
   - [On-Chain Atomic Swaps](https://blog.decred.org/2017/09/20/On-Chain-Atomic-Swaps/).
2. Изучить [Decred cross-chain atomic swapping](https://github.com/decred/atomicswap/) `(1-2 дня)`.
3. Разобраться и повторить, обменять [Ropsten ether на Rinkeby ether](https://medium.com/@DontPanicBurns/ethereum-cross-chain-atomic-swaps-5a91adca4f43) `(1-2 дня)`
4. Переделать контракты из пункта 3 , так чтобы, параметры задавались через конструктор при деплойменте контракта. Обменять Ropsten ether на Rinkeby ether `(1 день)`.
