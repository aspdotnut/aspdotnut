```cs
Console.Clear();
Console.WriteLine(Environment.NewLine +
                  @" █████╗ ██████╗  ██████╗ ██╗   ██╗████████╗    ███╗   ██╗██╗████████╗██╗    ██╗██╗████████╗" + Environment.NewLine +
                  @"██╔══██╗██╔══██╗██╔═══██╗██║   ██║╚══██╔══╝    ████╗  ██║██║╚══██╔══╝██║    ██║██║╚══██╔══╝" + Environment.NewLine +
                  @"███████║██████╔╝██║   ██║██║   ██║   ██║       ██╔██╗ ██║██║   ██║   ██║ █╗ ██║██║   ██║   " + Environment.NewLine +
                  @"██╔══██║██╔══██╗██║   ██║██║   ██║   ██║       ██║╚██╗██║██║   ██║   ██║███╗██║██║   ██║   " + Environment.NewLine +
                  @"██║  ██║██████╔╝╚██████╔╝╚██████╔╝   ██║       ██║ ╚████║██║   ██║   ╚███╔███╔╝██║   ██║   " + Environment.NewLine +
                  @"╚═╝  ╚═╝╚═════╝  ╚═════╝  ╚═════╝    ╚═╝       ╚═╝  ╚═══╝╚═╝   ╚═╝    ╚══╝╚══╝ ╚═╝   ╚═╝   " + Environment.NewLine +
                  Environment.NewLine);

Console.WriteLine("Welcome to NitWit's GitHub About Me!" + Environment.NewLine +
                  "This is a simple little piece of code that tells you some things about myself." + Environment.NewLine +
                  "Press any key to continue...");
Console.ReadKey();

while (true)
{
    Console.Clear();
    Console.WriteLine("---MENU---" + Environment.NewLine +
                      "1. About me" + Environment.NewLine +
                      "2. My projects" + Environment.NewLine +
                      "3. But why" + Environment.NewLine +
                      "4. Exit" + Environment.NewLine +
                      Environment.NewLine);
    
    Console.Write("Please make your choice: ");
    var isParsable = int.TryParse(Console.ReadLine(), out var menuSelector);
    if (!isParsable || menuSelector is < 1 or > 4)
    {
        Console.WriteLine("Please enter a valid number.");
        Console.WriteLine("Press any key to continue...");
        Console.ReadKey();
        continue;
    }
    switch (menuSelector)
    {
        case 1:
            Console.Clear();
            Console.WriteLine("---ABOUT ME---");
            Console.WriteLine("Name: NitWit" + Environment.NewLine +
                              "Age: Old enough to bang your mom" + Environment.NewLine +
                              "Job: Student slave" + Environment.NewLine +
                              "Hobbies: Crying myself to sleep" + Environment.NewLine +
                              "Languages: Dutch, English, Python, Javascript, Html, Php, peepee poopoo" + Environment.NewLine +
                              Environment.NewLine);
            
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            break;

        case 2:
            Console.Clear();
            Console.WriteLine("---MY PROJECTS - 1/5---");

            Console.WriteLine("Calculus! - Calculus! is a wallpaper engine web wallpaper that can do basic math and has a customizable font size, spin speed, and movement speed." + Environment.NewLine +
                              "https://steamcommunity.com/sharedfiles/filedetails/?id=2886716727" + Environment.NewLine + 
                              Environment.NewLine);
            
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            
            Console.Clear();
            Console.WriteLine("---MY PROJECTS - 2/5---");

            Console.WriteLine("Calculus! lite - Calculus! lite is a wallpaper engine web wallpaper based on Calculus!, but with every bit of customizability and logic scrapped out. " + Environment.NewLine +
                              "It serves no purpose other than acting as a spinning dvd logo screensaver." + Environment.NewLine +
                              "https://steamcommunity.com/sharedfiles/filedetails/?id=2887134455" + Environment.NewLine + 
                              Environment.NewLine);
            
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            
            Console.Clear();
            Console.WriteLine("---MY PROJECTS - 3/5---");
            
            Console.WriteLine("Calculus! extended - Calculus! extended is a wallpaper engine web wallpaper based on Calculus!, but with more logic in order to process more complex calculations. " + Environment.NewLine +
                              "Using Calculus! extended you'll be able to input a formula or anything else math in a text input, and the program will handle the rest." + Environment.NewLine +
                              "https://steamcommunity.com/sharedfiles/filedetails/?id=2889771142" + Environment.NewLine + 
                              Environment.NewLine);
            
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            
            Console.Clear();
            Console.WriteLine("---MY PROJECTS - 4/5---");
            
            Console.WriteLine("Calculus! web - Calculus! web is a website port of Calculus! extended for if you don't have wallpaper engine and still wish to mess around with it. " + Environment.NewLine +
                              "This version is currently heavily work in progress, as javascript doesn't want do control spin speed properly. " + Environment.NewLine +
                              "NOTE: Speed modifiers don't work" + Environment.NewLine +
                              "https://calculus.witted.nl/" + Environment.NewLine + 
                              Environment.NewLine);
            
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            
            Console.Clear();
            Console.WriteLine("---MY PROJECTS - 5/5---");
            
            Console.WriteLine( "ProxC - Cross Platform C# proxy" + Environment.NewLine +
                               "https://github.com/WittyCodehub/ProxC" + Environment.NewLine +
                               Environment.NewLine);
            
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            break;
        
        case 3:
            Console.Clear();
            Console.WriteLine("---BUT WHY---");
            Console.WriteLine("Because I can." + Environment.NewLine +
                              Environment.NewLine);
            
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            break;
        
        case 4:
            Console.Clear();
            Console.WriteLine("Goodbye!");
            Environment.Exit(0);
            break;
        
        default:
            Console.WriteLine("HOW THE FUCK DID WE GET HERE WHAT IS GOING ON AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA");
            
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            break;
    }
}

```
