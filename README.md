# Key images for dev and gov wallets

For transparency:

GOV wallet address: TvzXGov4tNr6jYG2gdox7bcuEBwwSTpQYAb6w7qgSxuu4hsxY9CMgMgaL6EeqVcQ6hS7Cppn73W8ZSMU8gLMi4N42yTShfkP9
Gov view key: a48251a25cbb210d9aac8b78fe7d6f15a63cd78840db042f94cf493b097b7805

DEV wallet address: Tw1XDEVkfVsRFhvjPQJgTjFi4uXDBiMomYeaaaj43SHPSTyLj8nBkdv2KBV8t9CzuCUy1fgYkk9tse6xA3B5oPJZ1jLfHLDrh
Dev view key: 7ffeb772829bc3ab917b634a55a67dc8e1c52546bc351c8f77eb3b0902bf3000

How to:

Copy key_gov in to directory with wallet-cli than

./wallet-cli --generate-from-view-key viewgov

After sync import key_gov

Command in wallet: import_key_images key_gov

You will see all IN OUT transactions

