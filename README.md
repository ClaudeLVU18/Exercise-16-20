//Mark my Words

#include <iostream>
#include <string>
  
int main()
{   
    cout << "Input the student's grade percentage: \n\n";
    double grd;
    cin >> grd;

    if ((grd == 70) || (grd >70))
    {
        cout << "\nThe student's final grade is an A.\n\n";
    }
    else if ((grd == 60) || (grd >60) && (grd<70))
    {
        cout << "\nThe student's final grade is a B.\n\n";
    }
    else if ((grd == 50) || (grd >50) && (grd<60))
    {
        cout << "\nThe student's final grade is a C.\n\n";
    }
    else if ((grd == 40) || (grd >40) && (grd<50))
    {
        cout << "\nThe student's final grade is a D.\n\n";
    }
    else
    {
        cout << "\nThe student's final grade is a F.\n\n";
    }
    

    return 0; 
}
  
//Starting a band

#include <iostream>
#include <string>
  
int main()
{   
    cout << "So you need a guitarist or a drummer for your band...\n\nYou need a guitarist or a drummer.\n\n";
    cout << "Take your friend with you.\n\n";
    cout << "Do they play an instrument?\n\n";
    cout << "\n\nYes or No:  ";

    string musicalFriend;
    
    cin >> musicalFriend;

    if((musicalFriend == "yes")||(musicalFriend =="Yes")||(musicalFriend =="YES"))
    {
        cout << "\n\nWhat instrument does he play?\n\n";
        cout << "\nGuitar or drums?\n\n";
        cout << "\nType in their instrument of choice: ";

    

        string friendPlays;
        cin >> friendPlays;

        if((friendPlays == "guitar") || (friendPlays == "Guitar") || (friendPlays == "Drum") || (friendPlays == "drum") || (friendPlays == "Drums") || (friendPlays == "drums")|| (friendPlays == "GUITAR")|| (friendPlays == "DRUM")|| (friendPlays == "DRUMS"))
        {
        cout << "\n\nGreat! Your friend plays the " << friendPlays << ". Your friend can join.";
        }
        else
        {
            cout << "\n\nSorry, that's not the instrumentalist your looking for.";
        }
    }
    else
    {
        cout << "\n\nSorry, they can't join";
    }


    return 0; 
}

//Killing time

#include <iostream>
#include <string>
  
int main()
{   
    cout << "You have arrived in Dubai Mall. \n\n";
    cout << "Now it's time to wait for your friend. \n\n";
    cout << "Press enter to continue... \n\n";
    cin.get();
    cout << "Your friend just messaged you. They say they will be late. \n\n";
    cout << "How late do you think they said they will be? \n\n";
    cout << "Minutes: ";
    
    double time;
    cin >> time;

    if (time > 14)
    {
        cout << "\nSince your friend is going to be " << time << " minutes late, you should go do something.\n";
        cout << "\nHow much money do you have?\n";
        cout << "\nAED: ";
        double cash;
        cin >> cash;
            
            if (cash > 4)
            {
                cout << "\nYou should go get some coffee.\n\n" << endl;
            }
            else
            {
                cout << "\nYou should go for a walk around town.\n\n" << endl;
            }
    }
    else
    {
        cout << "\nJust sit and wait for them at the food court.\n\n" << endl;
    }

    return 0; 
}

  
//Earthquake

#include <iostream>
#include <string>
  
int main()
{   
    cout << "Richter Scale desciptor. \n\n";
    cout << "Input an earthquake's magnitude: \n\n";
    double grd;
    cin >> grd;

    if ((grd > 10.0) || (grd == 10.0))
    {
        cout << "\nMeteoric level.\n\n";
    }
    else if ((grd == 8.0) || (grd >8.0) && (grd<10.0))
    {
        cout << "\nGreat level.\n\n";
    }
    else if ((grd == 7.0) || (grd >7.0) && (grd<8.0))
    {
        cout << "\nMajor level.\n\n";
    }
    else if ((grd == 6.0) || (grd >6.0) && (grd<7.0))
    {
        cout << "\nStrong level.\n\n";
    }
    else if ((grd == 5.0) || (grd >5.0) && (grd<6.0))
    {
        cout << "\nModerate level.\n\n";
    }
    else if ((grd == 4.0) || (grd >4.0) && (grd<5.0))
    {
        cout << "\nLight level.\n\n";
    }
    else if ((grd == 3.0) || (grd >3.0) && (grd<4.0))
    {
        cout << "\nMinor level.\n\n";
    }
    else if ((grd == 2.0) || (grd >2.0) && (grd<3.0))
    {
        cout << "\nVery minor level.\n\n";
    }
    else
    {
        cout << "\nMicro Level.\n\n";
    }

    return 0; 
}

