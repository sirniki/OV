Проверяет синтаксис плагином `eslint-plugin-cypress`.

Текущие правила: recommended
*✅ - находятся в recommended

| Name                                                                                                                                   | Description                                                        | 💼  |
| -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | --- |
| [assertion-before-screenshot](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/assertion-before-screenshot.md) | требовать assert перед скриншотом                                  |     |
| [no-assigning-return-values](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/no-assigning-return-values.md)   | запрещать присваивать результат выполнения команд `cy.` переменным | ✅   |
| [no-async-before](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/no-async-before.md)                         | запретить `async`/`await` в `before` блоках                        |     |
| [no-async-tests](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/no-async-tests.md)                           | запретить `async`/`await` в телах тестов                           | ✅   |
| [no-force](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/no-force.md)                                       | запретить `force: true`                                            |     |
| [no-pause](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/no-pause.md)                                       | запретить `cy.pause()`                                             |     |
| [no-unnecessary-waiting](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/no-unnecessary-waiting.md)           | запретить использование wait как таймера                           | ✅   |
| [require-data-selectors](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/require-data-selectors.md)           | требовать обращаться только по `data-*` селекторам                 |     |
| [unsafe-to-chain-command](https://github.com/cypress-io/eslint-plugin-cypress/blob/HEAD/docs/rules/unsafe-to-chain-command.md)         | запретить действия в длинных цепочках                              | ✅   |
