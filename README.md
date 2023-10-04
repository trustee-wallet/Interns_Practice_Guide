# Trustee Smart-contracts practice

## Solidity

#### Материалы
1. [Solidity doc](http://solidity.readthedocs.io/en/develop/)
2. [Рекомендации по оформлению кода на Solidity](http://solidity.readthedocs.io/en/develop/style-guide.html)
3. [Распространенные шаблоны и подходы при написании смарт-контрактов](http://solidity.readthedocs.io/en/develop/common-patterns.html)
4. [Cryptozombies](https://cryptozombies.io/)

#### Задачи
1. Материалы для ознакомления `(1-2 дня)`:
   - [Понятие смарт-контракта](https://forklog.com/chto-takoe-smart-kontrakt/);
   - [Введение в разработку умных контрактов Ethereum](https://habrahabr.ru/post/335710/);
   - [Разработка умных контрактов на Solidity](https://habrahabr.ru/post/312008/).
2. Написать свой самый простой ERC-20 токен (скомпилировать в Remix или Truffle, закинуть в любой TestNet, предоставить ссылку на контракт, показать тестовые транзакции по переводу токенов между несколькими (минимум 3) адресами.
   Перевод токенов можно осуществить с помощью MyEtherWallet. `(2 дня)`
   Материалы по созданию и запуску токенов:
   - [Создание и запуск токенов - быстро и весело](https://medium.com/bitfwd/how-to-issue-your-own-token-on-ethereum-in-less-than-20-minutes-ac1f8f022793);
   - [А теперь - фундаментально и качественно](https://www.ethereum.org/token).

     Необходимые для выполнения задания материалы и сервисы:
   - [ERC-20 token standard](https://theethereum.wiki/w/index.php/ERC20_Token_Standard);
   - [Remix](https://remix.ethereum.org/);
   - [Truffle github](https://github.com/trufflesuite/truffle/);
   - [MyEtherWallet](https://www.myetherwallet.com/);
   - [MetaMask](https://metamask.io/);
3. Опубликовать исходный код контракта в TestNet `(1 день)`.
4. Изучить контракт [токена Edgeless](https://etherscan.io/token/Edgeless) и разобраться чем он отличается от стандартного ERC20 токена `(1 день)`.
   - [код контракта на Solidity](https://github.com/EdgelessCasino/Smart-Contracts);
5. Написать свой ERC-20 токен с возможность сжигания определенного количества токенов после определенной даты (закинуть на TestNet, предоставить ссылку на контракт, показать тестовые транзакции по переводу токенов между несколькими (минимум 3) адресами `(1 день)`.
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

## Web3.js (Node.JS lib)
[Web3 doc](https://web3js.org/)

1. Научиться определять баланс ETH на заданном адресе `(1 день)`.
2. Научиться передавать ETH программно `(1 день)`.
3. Реализовать возможность деплоймента контракта с начальными параметрами переданными в конструктор `(1 день)`.
4. Реализовать простой скрипт распределения ERC20 токенов от имени владельца (на входе массив с адресами и количеством токенов для каждого адреса) `(1-2 дня)`.
5. Написать скрипт определения баланса ERC20 токенов заданного контракта на адресе (списке адресов) `(1-2 дня)`.
