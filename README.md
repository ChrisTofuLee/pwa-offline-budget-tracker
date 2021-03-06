# pwa-on-offline-budget-tracker

The offline budget tracker allows the user to add expenses and deposits to their budget with or without an internet connection. When entering transactions offline, they will populate the total when brought back online.

## Instillation
Simply go to the application [here](https://guarded-lake-09073.herokuapp.com/) to try out the application. If running through a local host, ensure you install the necessary dependencies before running npm run start within the terminal. 

## Usage
When the user enters the application they will be able to enter a transaction name and amount then select whether to add or subtract funds. Once entered they will be presented with the current total funds, followed by the list of transactions (amount and name of transaction) and finally a graph to show the fluctuation of funds with each entry point with a date stamp on them.

If the user goes offline, they will still be able to add and subtract funds into the app which will stored in the service worker. When back online, the entries will be updated into the database showing the new total and updated graph following from the offline mode.

## example

- image 1: Budget Tracker in Offline Mode
![application view](./src/Develop/1.png)