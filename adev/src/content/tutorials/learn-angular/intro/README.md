.
const express = require('express');

const app = express();

const port = 3000;

app.use(express.json());

let users = [];

let snaps = [];

app.post('/login', (req, res) => {

const { username, password } = req.body;

// user authentication logic yahaan aayeg

}); res.json({ message: 'Login successful' })

app.post('/register', (req, res) => {

const { username, password } = req.body;

// user registration logic yahaan aayega

}); res.json({ message: 'Registration success

app.get('/snaps', (req, res) => {

res.json(snaps);

});

app.post('/sendSnap', (req, res) => {

const { from, to, snap } = req.body;

// snap sending logic yahaan aayega

}); res.json({ message: 'Snap sent successful

app.listen(port, () => {

}); console.log(Server started on port ${port

Ab, frontend ke liye:
