This is a file that outlines a general improvements list for My Waydroid Manager;
Contributions working on the following is welcome!


General Guidelines:

  - As of the moment, I am not really interested in doing the UI in XML, please refrain from suggesting it.
  - Be kind, Curtious, and patient when making contributions.
  - Improvements that expand the covered distributions / Desktop Enviroments are welcome, if you have hardware
    to test your proposed improvements on (f/oss devs aren't rich).
  - Any system functions need to be defined in their own bash script in /scripts
    ** I would like to eventually consolidate everything into subprocess.run commands
       once I know enough to do so, and ditch the scripts entirely.
  - All GUI components need to be made with Gtk4, Libadwaita, and Python.
  - I am not a senior developer, please do not assume that I know everything.
  

Things to be fixed, Finished, or implimented:


  - A correct 'Back' Button that destroys the currently open window while opening the previous

  - A better 'About' Button using Adw.AboutWindow
    ** Help with this is appreciated!

  - Replace $hostname as the method of distribution identification with something more robust

  - Add support for, and test Manjaro

  - Add support for and test Postmarket OS (eventually)

  - Add support for more distributions and desktop enviroments

  - Setup translation files (help needed)

  - Package for Flatpak (help needed)

  - Package for AUR (help needed)

  - Package for *your choice of distribution here* (help needed!)

  - Add 'donation' link to the 'About' page (help definitely appreciated!)
