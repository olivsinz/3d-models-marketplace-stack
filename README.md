## Inspiration
 - https://thangs.com/
 - https://free3d.com/

## List of features to be developed for v1
### Guest/Unauthenticated users
- [ ] Login
- [ ] Register (with email verification)
- [ ] Reset password
- [ ] Login with Facebook
- [ ] Login with Google

### Authenticated users
- [ ] Enable/disable 2FA
- [ ] Change password
- [ ] Edit profile information (full name, profile picture)
- [ ] View profile
- [ ] Users can follow/unfollow other users.
- [ ] Add profile picture
- [ ] Each user can add their skills and experience as tags to their public profile.
- [ ] Each user can edit their skills and experience
- [ ] A user has a public profile where he can find the designs (free and premium) he has uploaded

### 3D models
- [ ] Users can upload 3d models
- [ ] Users can sell 3D digital models
- [ ] Users can buy 3D digital models
- [ ] Users can download the free templates without logging in.
- [ ] Users can find the 3D models of users they follow in a page called "explore".
- [ ] Uploaded 3D models for sale must be confirmed by an administrator before being published.
- [ ] User can find his uploaded and purchased models in his profile (dashboard).

### Search
- [ ] A user can search for 3d models from the home page.
- [ ] Users can search for 3d models from his profile (dashboard) (search by tags, description, model name, designer name)
- [ ] A user can filter models on the home page
- [ ] A user can filter models from his profile (dashboard) (most downloded, most viewed, new, free/premium models).

### Payment
- [ ] Integration of "Paymee" as a payment method

### Cash-out requests
- [ ] Make a cash-out request
- [ ] User can view a history of his cash-out requests

### Platform management (Admin only)

#### Generals
- [ ] View a user details
- [ ] List of all registered users
- [ ] Statistics about uploaded 3D models (free and premium)

#### Cash-out requests
- [ ] Approve a cash-out request
- [ ] Reject a cash-out request
- [ ] Listing of cash-out requests

## Database architecture
To be done after validation of all points

## Navigation

### Main navigation
- Home
- Free 3D models
- Paid 3D models
- Login
- Create an account

### Second navigation
- FAQ
- Contact us
- Terms of Service
- Privacy Policy

# Use Cases (workflow)
1. A user can create an account with his username, an email address, and a password.
2. A user should receive a verification link after registration by email.
3. A user must be able to validate his account by email.
4. A user must be able to login with his email and password or Facebook/Google.
5. Each user can add their skills and experience as tags to their public profile.
6. Each user can add profile picture to their public profile
7. The last two passwords can no longer be accepted when changing password.
8. A user must be able to reset his password.
9. A user can upload free or premium 3D models.
10. Each model has a name, description, tags, upload date, images, and source file.
11. When a user uploads a 3D model for sale, an administrator must confirm the model before posting it.
12. When a user sells a model, the money is added to his account (profile).
13. The user can find his uploaded and purchased models in his profile (dashboard).
14. After selling a model, the user can make a cash-out request (not related to the payment method, just a simple request to the administrator). When the administrator approves the cash-out request, the amount of money in the user's profile returns to 0.


# Technos

## Backend
- Laravel + Livewire/Inertia
- Database: MySQL

## Frontend
- Framework CSS : Tailwind CSS

NB: Some points that are too technical (unit tests for work safety, deployment, etc.) are deliberately omitted for the simplicity of the document. They will be treated during the execution of the project.
