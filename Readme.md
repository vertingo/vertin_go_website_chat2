
# Socket.IO Chat

A simple chat demo to demonstrate WebSockets support on www.evennode.com Node.js hosting platform.

## How to use

```
$ cd socket.io-chat-example
$ npm install
$ node .
```

And point your browser to `http://localhost:3000`. Optionally specify
a port by supplying the `PORT` env variable.

## Features

- Multiple users can join a chat room by entering a unique username
on website load.
- Users can type chat messages to the chat room
- A notification is sent to all users when a user joins or leaves
the chatroom

Start the application locally

To start the application, run the following command from the root of the project.
`` `
Node server
`` `

The application is now accessible to the url ** http: // localhost: 3000 / **.

## Deployed your application via Git on EvenNode.com (https://admin.evennode.com/login?continue=http%3A%2F%2Fadmin.evennode.com%2Fa%2Flist)
If you do not have an account git create your account at the following URL: https://github.com/business?utm_source=google&utm_medium=cpc&utm_term=git&utm_campaign=2018q1-adv-EMEA|NB|Git|FR|EN|EX|20160906
Downloaded and installed also git locally so you can run the commands below! ==> https://git-scm.com/download/win

Then run the following commands in your project directory via a command prompt (Right Click + Shift ==> Open Command Prompt!) to instantiate a local git repository:

```
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/vertingo/vertin_go_website_chat.git
git push -u original master
```
If you encounter this kind of error: fatal: refusing to merge unrelated stories
Execute the command below: git pull origin branchname --allow-unrelated-histories

Once your project uploads into your git repository you connect to EvenNode (https://admin.evennode.com/login?continue=http%3A%2F%2Fadmin.evennode.com%2Fa%2Flist)
And create your EvenNode account for free to deploy your application on the web!
Then create a new application by clicking the create new app button!

-Downloaded now putty: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
-Click on the generate button
-Move your mouse over PuttyGen until your key is generated
-Click on the menu Conversion -> Export OpenSSH key
-Saved your private key in the following directory: C: \ Users \ your_username \ .ssh \ id_rsa
-Copy your public key to your EvenNode account in the manage Puclic Key menu

Go back to your root folder of your project and execute the following command line:

For this command you must replace the part your_app_here with your git directory key to your EvenNode account
For example, the part between the hook (do not include the hook) in the following example: git@git.evennode.com: [b3d71189e8e580bb1944b02145721033.git]

```
git remote add evennode git@git.evennode.com: your_app_here
git push evennode master
```
And now your application is now online on your EvenNode account!

```
A little boost follow us on YouTube and Facebook!
[You Tube]: https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1
[Facebook]: https://www.facebook.com/vertingo/
```
## License

MIT