#include <iostream>
#include <stdlib.h>
#include <time.h>
int main() {
//variable to exit progam
int i = 0;
//-=-=-=-=-=-=-=-=-=-
    int pass;
    std::cout << "Welcome back Jonas enter password to continue\n";
    std::cout << "Enter Password:";
    std::cin >> pass;
// variables for all programs inside cases-----------------------------------------------------
// dog years case #222222-2-2-2-2-2-2-2-2-2-2-2-2-2-2-2-2-2-2-2-22-2-2-2-2-2-2-2-2-2-2-2
 int age;
 int early_years;
 int later_years;
 int human_years;
// legal drinking age program variables case #3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3-3--3-33--3-3-33-3-3-3--3-3-3-3-3
 int a; // for age of user
// spirit animal program variables starts on line 79 case 4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4-4
int Q,W,E;
std::string Donk = "Donky ";
std::string Monk = "Monkey ";
std::string Pony = "Pony ";
std::string Toad = "Toad ";
std::string Dog = "Dog ";
std::string Cat = "Cat ";
std::string Bird = "Bird ";
std::string Pig = "Pig ";
std::string Cow = "Cow ";
// magic 8 ball variable
int answer;

//
    while (pass != 1738 ){
    std::cout << "Incorrect password try again\n";
    std::cin >> pass;
}
    if (pass == 1738){
    std::cout << "acces granted\n\n\n\n";
    }
// trying while statment 
while (i<5){

// opyions for cases 
int Option;
std::cout << "Enter options 1-5 launch a previously built program\n";
std::cout << "This program is set to run 5 times before closing unless you have selected exit\n\n";
std::cout << "1: Hello world program\n";
std::cout << "2: Dog year program\n";
std::cout << "3: Legal drinking age program\n";
std::cout << "4: Spirit animal Program\n";
std::cout << "5: Magic 8 ball\n";
std::cout << "6: Exit\n";
std::cin >> Option;


switch (Option){
//Case 1111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111
    case 1:
    std::cout << "Hello Digus\n\n\n";
    i++;
    break;
//case 2222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222
    case 2:
     std::cout << "Enter your dogs current age to get human age\n";
     std::cin >> age;
{
    early_years = 30;
    later_years = (age-2)*4;
    human_years = (early_years+later_years);
}
    std::cout << "Your dog is approximitly " << human_years << " in human years\n\n\n";
   i++;
   break;
//case 3 333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333323333333333
  case 3:
  {
  a = 0;
  }
  std::cout << "Enter age to see if you can drink (legally)\n\n\n";
  std::cin >> a;

  if ( a >=21) {
  std::cout << "You are the legal drinking age\n\n\n";
  }
    else if ( a < 21) {
   std::cout << "bruh moment\n\n\n";
}
i++;
break;
    
    //case 4444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444444
    case 4:
std::cout << "get spirit animal with accesory enter value 1-10\n"; 
std::cin >> Q ;

switch (Q) {

case 1:

std::cout << "donkey, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10){
std::cout << Donk << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Donk << "with a Cowboy hat\n";
}
else {
std::cout << Donk << " with a Mini Cooper hat\n";
}

break;

case 2:
std::cout << "Monkey, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Monk << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Monk << "with a Cowboy hat\n";
}
else {
std::cout << Monk << " with a Mini Cooper hat\n";
}
break;

case 3:
std::cout << "Pony, Enter another value 1-100 to get accesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Pony << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Pony << "with a Cowboy hat\n";
}
else {
std::cout << Pony << " with a Mini Cooper hat\n";
}
break;

case 4:
std::cout << "Toad, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Toad << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Toad << "with a Cowboy hat\n";
}
else {
std::cout << Toad << " with a Mini Cooper hat\n";
}
break;

case 5:
std::cout << "Dog, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Dog << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Dog << "with a Cowboy hat\n";
}
else {
std::cout << Dog << " with a Mini Cooper hat\n";
}
break;

case 6:
std::cout << "Cat, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Cat << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Cat << "with a Cowboy hat\n";
}
else {
std::cout << Cat << " with a Mini Cooper hat\n";
}
break;

case 7:
std::cout << "Cat, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Cat << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Cat << "with a Cowboy hat\n";
}
else {
std::cout << Cat << " with a Mini Cooper hat\n";
}
break;

case 8:
std::cout << "Bird, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Bird << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Bird << "with a Cowboy hat\n";
}
else {
std::cout << Bird << " with a Mini Cooper hat\n";
}
break;

case 9:
std::cout << "Pig, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Pig << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Pig << "with a Cowboy hat\n";
}
else {
std::cout << Pig << " with a Mini Cooper hat\n";
}
break;

case 10:
std::cout << "Cow, enter another value 1-100 to get acesory\n";
std::cin >> W;
if(W >0 && W<=10) {
std::cout << Cow << "with a hat\n";
}
else if(W >10 && W <=50) {
std::cout << Cow << "with a Cowboy hat\n";
}
else {
std::cout << Cow << " with a Mini Cooper hat\n";
}
i++;
break;
}

// case 55555555555555555555555555555555555555555555555555555555555555555555555555555555555555555555555555555555
 
 case 5:
 {
 std::cout << "Magic 8-Ball:\n\n";
 
 srand(time(NULL));
 answer = std::rand() % 10;
 


if (answer == 0) {
 std::cout << "It isnt certain\n\n";
}
else if (answer == 1){
  std::cout << "Signs point to sytem error restart.\n\n";
}
else if (answer == 2){
  std::cout << "Ask again later.\n\n";
}
else if (answer == 3){
  std::cout << "Don't count on it.\n\n";
}
else if (answer == 4){
  std::cout << "Cannot predict now.\n\n";
}
else if (answer == 5){
  std::cout << "Outlook not so good.\n\n";
}
else if (answer == 6){
  std::cout << "Concentrate and ask again.\n\n";
}
else if (answer == 7){
  std::cout << "Don't count on it.\n\n";
}
else if (answer == 8){
  std::cout << "Without a doubt.\n\n";
}
else if (answer == 9){
  std::cout << "Honsrtly couldent tell ya.\n\n";
}
else {
  std::cout << "I wish i knew.\n\n";
}
i++;
 }
break;
// case 6 exit666666666666666666666666666666666666666666
case 6: 
i++;
i++;
i++;
i++;
i++;
break;








}

            }           
                    
}
