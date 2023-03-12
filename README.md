# App

GymPass style app.

## FR (Functional Requirements)

- [ ] Should be able to sign up;
- [ ] Should be able to authenticate;
- [ ] Should be able to get the logged in user's profile;
- [ ] Should be able to get the logged in user's check-in count;
- [ ] Should be able to get the logged in user's check-in history;
- [ ] Should be able to get nearby gyms;
- [ ] Should be able to search gyms by name;
- [ ] Should be able to check-in in a gym;
- [ ] Should be able to validate the logged in user's check-in;
- [ ] Should be able to register up a gym;

## BR (Business Rules)

- [ ] User should not be able to sign up with a duplicated email;
- [ ] User should not be able to check-in more than 1 time a day;
- [ ] User should not be able to check-in if not close (100m) to the gym;
- [ ] Check-in can only be validate until 20 minutes past created;
- [ ] Check-in can only be validated by admins;
- [ ] Gym can only be registered by admins;

## NFRs (Nonfunctional Requirements)

- [ ] User's password should be crypted
- [ ] App's data should persist in a PostreSQL database;
- [ ] All lists should use pagination with 20 itens per page;
- [ ] User should be identified by a JWT;



