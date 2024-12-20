# PLAN:
The basic idea is to make an app (react native) that will allow the user to create objects and generate pdf's with qr codes that link to the objects. The app will also have a scan function that will allow the user to scan the qr codes and get the object id / url in return. The entire thing will run on docker containers with a postgres database for storing the objects. The end goal is to use the code in a larger platform used to managed storage centers.

# Stack:
- React Native
- Docker
- Postgres
- Express
- Node
- Typescript
- Tailwindcss

# Todo:
- [x] Create a basic react native app
- [ ] Create a basic express server
- [ ] Create a basic postgres database
- [ ] Create a basic docker container for the app
- [ ] Build ui for frontend with scanner and object creation
- [ ] Build api endpoint for creating, editing and deleting objects
- [ ] Build api endpoint for scanning qr codes