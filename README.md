- 👋 Hi, I’m Adri
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Adrixy78/Adrixy78 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

void Pacman::replacing(int value){
	Pacman * p = reinterpret_cast<Pacman *> (value);
	p->_xcoord = 0;
	p->_ycoord = 2;
	p->setDirection(DOWN);
	p->_isDead=false;
}
