Send a `Take` tx to [Faucet Contract](https://explorer-test.aelf.io/contract?#https%3A%2F%2Fexplorer-test.aelf.io%2Fviewer%2Faddress.html%23%2Fcontract%2F2M24EKAecggCnttZ9DUUMCXi4xC67rozA87kFgid9qEwRUMHTs) deployed to AElf TestNet MainChain to get some ELF tokens of AElf Testnet.

Currently the url https://aelf-test-node.aelf.io is available.

# Use aelf-command
Refer to [send-a-transaction-by-aelf-command](https://docs.aelf.io/en/latest/reference/cli/methods.html#send-send-a-transaction).

Useful Information:
- `the URI of an AElf node`: https://aelf-test-node.aelf.io
- `the address of contract`: 2M24EKAecggCnttZ9DUUMCXi4xC67rozA87kFgid9qEwRUMHTs
- Select the `Take` method
- Each aelf account can take 100 ELF tokens from this contract every 3 hours.

# Use AElf.Cli
Refer to [AElf.Cli](https://github.com/AElfProject/aelf-cli)

- Config the cli tool with your own aelf account.
- Use `aelf take` command to take ELF tokens.

You can downgrade the AElf releated packages to `1.1.0` or add the following source to your nuget config if this myget source ain't load automatically:
```
https://www.myget.org/F/aelf-project-dev/api/v3/index.json
```
