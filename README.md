start main


while(choice != 3) {
    dsiplay "Enter your command: "
string command = readline()
if (command == "1"){
    GetFull()
    break loop
}
else if (command == "2"){
    GetPartial()
    break loop
}
else {continue loop;}

}
} 

end main


static void GetFull(){
random rnd = new Random();      //est. random
int numRows = rand.next(3,9)    // choose random between 3-9


    for (int i = 1; i <= numRows; i++){  // main loo (controls rolls)
        for (int x = 1; x <= i; x++){  //nested loop (controls colls)
            write "() "                 // write prints out this on same line
        }
        writeline "() "          //print on new line
    }
}

static void GetPartial{

    random rnd = new Random();      //est. random
int numRows = rand.next(3,9)    // choose random between 3-9
ranadom yesNo = new Random()


    for (int i = 1; i <= numRows; i++){ 
        for (int x = 1; x <= i; x++){ 
            int yesNo = rand.next(2)
            if (yesNo == 1){  // if the random number is 1 we do not have a piece of triangle there
                write " "
            }
            else{
            write "() " // if the number is 2 we do have a piece of the triangle
            }             
        }
        writeline "() "
    }
}
}

