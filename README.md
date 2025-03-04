

## Features
1. Signup and signin authentication
2. Forgot password and reset password
3. Change password when logged in
4. Create, read, update and delete posts
5. Post reactions
6. Comments
7. Followers, following, block and unblock
8. Private chat messaging with text, images, gifs, and reactions
9. Image upload
10. In-app notification and email notification

## Main tools
- Node.js
- Typescript
- MongoDB
- Mongoose
- Redis
- Express
- Bull
- PM2
- AWS
- Terraform
- Nodemailer
- Sendgrid mail
- Cloudinary
- Jest
- Lodash
- Socket.io


## Local Installation

- There are three different branches develop, staging and main. The develop branch is the default branch.

```bash
git clone -b develop https://github.com/uzochukwueddie/chatty-backend.git
cd chatty-backend
npm install
```
- To start the server after installation, run
```bash
npm run dev
```
- Inside the `setupServer.ts` file, comment the line `sameSite: 'none'`.
- You'll need to uncomment that line again before you deploy to AWS.

Make sure mongodb and redis are both running on your local machine.





