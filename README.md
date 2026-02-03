# Chain Link

This is the main repository for the Chain Link project, orchestrating the smart contracts, backend server, and client application.

## Project Structure

The project is organized into three main submodules:

- **[`contract`](https://github.com/thisha-me/chain-link-contract)**: Contains the Solidity smart contracts.
- **[`server`](https://github.com/thisha-me/chain-link-server)**: Contains the backend server implementation.
- **`client/`** (TBD): Contains the frontend client application.

## Setup

To clone the repository with all submodules:

```bash
git clone --recursive https://github.com/thisha-me/chain-link-main.git
```

If you have already cloned the repository without submodules:

```bash
git submodule update --init --recursive
```

## Updating Submodules

To update the submodules to their latest commits:

```bash
git submodule update --remote --merge
git add .
git commit -m "Update all submodules"
git push
```

This will fetch the latest changes from the remote repositories and merge them into your local submodules, then commit and push the changes to the main repository.

## Running the Project

Please refer to the README files in each submodule for specific instructions on how to run them.

- [Contract README](contract/README.md)
- [Server README](server/README.md)
