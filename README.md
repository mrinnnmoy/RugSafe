# RugSafe

Rug Detection API to decode and preview transactions for enhanced user safety in WEB3.

## ⚠️ Problem to Solve. 

Lots of users, even those considered as "Crypto natives," have lost thousands of dollars (if not millions) by signing scam transactions that they didn't fully understand. Rugs & scams are a problem we must solve to onboard the next billion users into Web3 safely.

## ✅ Possible Solution.

**RugSafe** is an API designed to provide human-readable previews of unsigned transactions, enhancing transparency and trust by:

1. **Readable Transaction Previews**: Decodes writable accounts and provides a clear breakdown of what the transaction is attempting to access.
   
2. **Proactive Defense**: Helps users identify malicious or unintended transaction requests before signing.

3. **Enhanced Security**: Works as an additional layer of protection for wallets and crypto transactions.

4. **User-Friendly Integration**: Compatible with existing Web3 wallets for seamless user adoption.

The transaction preview could look like:
> “This transaction is requesting access to your USDC account, staking accounts, etc.”

## ⚙️ Architecture.

![RugSafe Architecture](./)
[Excalidraw File...](./)

## 🛠 Tools, Languages & Frameworks used.

- **ReactJS:** Frontend library for creating user interfaces to interact with the API.
- **Node.js:** Backend runtime environment to handle API requests and responses.
- **Express.js:** Framework for building RESTful APIs for transaction decoding.
- **Helius XRAY:** Tool for decoding and interpreting blockchain transactions.
- **Blowfish:** Proactive defense system for enhancing wallet security.

## 📂 Folder Structure.

* **client:** Contains the frontend codebase for integration and user interaction.
* **server:** Contains the backend codebase, including the transaction decoding logic.

## 🧑‍💻 Contributions to this repo are WELCOME.👋

* 🎨 Any improvements to the design and UI are welcome.
* 🔨 Try to break the API by testing it rigorously. If you find any bugs, check if there’s already an open issue. If not, create a new one to report it.

## 🔃 Steps to be followed in order to make valid contributions to this repo.

**1.** Fork the [RugSafe](https://github.com/mrinnnmoy/RugSafe) repo by clicking on the fork button at the top of the page. This will create a copy of this repository in your account.

**2.** Clone the forked repository.

        git clone "https://github.com/<your-github-username>/RugSafe"

* Download and install Node.js v16.16.0.
* Download and install Git.
* Go to the terminal of your code editor and run `npm install` to download packages.
* Run `npm run dev` to start a local server.

**3.** Make necessary changes and commit those changes.  
Remember never to push anything to the Main branch.  

Always switch to the "develop" branch using:

    git checkout develop

Verify your current branch using:

    git branch

It should point to `*develop`.

Now add your changes using:

    git add <files-you-edited>

If there are multiple files, you can use:

    git add .

Create a commit message using:

    git commit -m "<commit-message-goes-here>"

**4.** Push changes to GitHub.

    git push origin develop

**5.** Create a Pull Request 👋

Go to your repository on GitHub, and you’ll see a `Compare & pull request` button. Click on it and write a summary of the changes you've made (attach images if required). The changes will be reviewed, and if they pass all tests, they’ll be merged. ❤️
