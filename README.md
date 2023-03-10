{
"name": "nodejs-ts-express-lecture",
"version": "1.0.0",
"description": "Example project with ts and express",
"main": "index.js",
"scripts": {
"dev": "tsnd --respawn src/index.ts",
"build": "tsc",
"start": "echo 'KLUM'",
"test": "mocha -r ts-node/register src/**/*.test.ts",
"test:jest": "jest src/foo.spec.ts",
"read-users": "ts-node src/demos/users.ts",
"show-env": "ts-node src/demos/env.ts"
},
"repository": {
"type": "git",
"url": "git+ssh://git@github.com/grunitech/nodejs-ts-express-lecture.git"
},
"author": "Grunitch Students",
"license": "ISC",
"bugs": {
"url": "https://github.com/grunitech/nodejs-ts-express-lecture/issues"
},
"homepage": "https://github.com/grunitech/nodejs-ts-express-lecture#readme",
"devDependencies": {
"@types/body-parser": "^1.19.2",
"@types/chai": "^4.3.4",
"@types/cors": "^2.8.13",
"@types/express": "^4.17.15",
"@types/mocha": "^10.0.1",
"@types/node": "^18.11.17",
"@types/pg": "^8.6.6",
"@types/supertest": "^2.0.12",
"@types/validator": "^13.7.10",
"chai": "^4.3.7",
"mocha": "^10.2.0",
"supertest": "^6.3.3",
"ts-jest": "^29.0.3",
"ts-node": "^10.9.1",
"ts-node-dev": "^2.0.0",
"typescript": "^4.9.4"
},
"dependencies": {
"body-parser": "^1.20.1",
"cors": "^2.8.5",
"express": "^4.18.2",
"pg": "^8.8.0",
"validator": "^13.7.0"
}
}
