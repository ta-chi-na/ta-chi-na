#include <cs50.h>
#include <stdio.h>

int main(void)
{
    // Prompt user to agree to something
    // get_string("Do yopu agree");
    // *char* when you only care about a single letter
    char c = get_char("Do you agree? ");

    // Check whether user agreed
    // "or" is represented by '||'
    if (c == 'y' || c == 'Y')
    {
        printf("Agreed.\n");
    }
    else if (c == 'n' || c == 'N')
    {
        printf("Not agreed.\n");
    }
    // User is ignored if the proper lettering is not used (y or n)
}
