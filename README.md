#include <iostream>
using namespace std;

int main() {
	//variables to hold onto each princess' score:
	int Gryffindor{};
	int Hufflepuff = 0;
	int Slytherin = 0;
	int Ravenclaw = 0;
	char choice; //variable to hold user input

	cout << "What  Harry Potter house are you?" << endl;

	//question 1
	cout << "What's your favorite color? (r)red, (y)yellow, (b)blue ,or (g)green" << endl;
	cin >> choice;
	if (choice == 'r')
		Gryffindor = Gryffindor + 1; //long way to add one
	else if (choice == 'y')
		Hufflepuff += 1; //shorter way to add one
	else if (choice == 'b')
		Ravenclaw ++; //shortest way to add one
	else if (choice == 'g')
		Slytherin ++; //shortest way to add one
	else
		cout << "not an option, dummy" << endl;

	cout << "what is your favorite element?(w)water (e)earth f(fire) a(air)" << endl;
	cin >> choice;
	if (choice == 'f')
		Gryffindor++;
	else if (choice == 'e')
		Hufflepuff++;
	else if (choice == 'a')
		Ravenclaw++;
	else if (choice == 'w')
		Slytherin ++;
	else
		cout << "not an option" << endl;

	cout << "What animal would you pick?(l)lion, s(snake) e(eagle), or b(bager)" << endl;
	cin >> choice;
	if (choice == 'l')
		Gryffindor++;
	else if (choice == 'b')
		Hufflepuff++;
	else if (choice == 'e')
		Ravenclaw++;
	else if (choice == 's')
		Slytherin++;
	else
		cout << "not an option" << endl;

	cout << "what are you? (f)Fighter, (l) Lover, (p)Protector or (c) caregiver "<< endl;
	cin >> choice;
	if (choice == 'p')
		Gryffindor++;
	else if (choice == 'l')
		Hufflepuff++;
	else if (choice == 'c')
		Ravenclaw++;
	else if (choice == 'f')
		Slytherin++;
	else
		cout << "not an option" << endl;

	cout << "what wand would you pick (wand materials)? (H)hand painted resin, (P)phenix feather core, (A)Acacia (y) yew" << endl;
	cin >> choice;
	if (choice == 'p')
		Gryffindor++;
	else if (choice == 'h')
		Hufflepuff++;
	else if (choice == 'a')
		Ravenclaw++;
	else if (choice == 'y')
		Slytherin++;
	else
		cout << "not an option" << endl;
	cout << "How would you like to be known to history? (w)the wise ,(g)The good,(b)The bold (t)The great"<<endl;
	cin >> choice;
	if (choice == 'w')
		Gryffindor++;
	else if (choice == 'g')
		Hufflepuff++;
	else if (choice == 't')
		Ravenclaw++;
	else if (choice == 'b')
		Slytherin++;
	else
		cout << "not an option" << endl;

	
	cout << "What kind of instrument most pleases your ear? (v)Violin ,(d)Drums,(p)piano (t)Trumpet" << endl;
	cin >> choice;
	if (choice == 'p')
		Gryffindor++;
	else if (choice == 'd')
		Hufflepuff++;
	else if (choice == 'v')
		Ravenclaw++;
	else if (choice == 't')
		Slytherin++;
	else
		cout << "not an option" << endl;

	cout << "what are you scared of the most? (g)Giant spider,(h)heigths,(c)claustrophobia  or (t)Trypanophobia(needles)" << endl;
	cin >> choice;
	if (choice == 'g')
		Gryffindor++;
	else if (choice == 'c')
		Hufflepuff++;
	else if (choice == 'h')
		Ravenclaw++;
	else if (choice == 't')
		Slytherin++;
	else
		cout << "not an option" << endl;

	cout << "what number do you like? (s)7(f)4,(o)07,(t)12" << endl;
	cin >> choice;
	if (choice == 's')
		Gryffindor++;
	else if (choice == 'f')
		Hufflepuff++;
	else if (choice == 'o')
		Ravenclaw++;
	else if (choice == 't')
		Slytherin++;
	else
		cout << "not an option" << endl;


	if (Gryffindor > Hufflepuff && Gryffindor > Ravenclaw && Gryffindor > Slytherin)
		cout << "your are A Gryffindor " << endl;
	else if (Hufflepuff > Ravenclaw && Hufflepuff > Slytherin)
		cout << "you are a Hufflepuff" << endl;
	else if (Ravenclaw > Slytherin)
		cout << "you are a ravenclaw" << endl;
	else
		cout << "you are a slytherin" << endl;



}
