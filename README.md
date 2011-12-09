wpftoolkit -- some stuff that ended up in .NET 4
====================================

## DESCRIPTION

wpftoolkit is an abandoned bit of source code from microsoft which ran on 
.NET 3.5. Much of it has been incorporated into .NET4. It is still of interest
to anyone who must continue to support .NET 3.5. Of most interest is the 
DataGrid control which was missing when WPF first launched and the View State Manager
(VSM) that is in 4.0 and used in Silverlight.

#Do not confuse wpftoolkit with the wpf extended toolkit.

* wpftoolkit is at https://wpf.codeplex.com/
* wpf extended toolkit is at https://wpftoolkit.codeplex.com/   
* ^^^ yes this is confusing

## INSTALLATION

The best way to install WPF Toolkit is to download the zip file from codeplex.

The Feb2010 codeplex release has some known bugs and some limited features, 
if you need those bugs fixed or to use added features you will need to build
from source. Clone from github and build.

## RUNNING

* Add reference to the wpftoolkit.dll assembly in your project.
* Add import the toolkit xml namespace into your xaml. I like to use the toolkit alias.
  xmlns:toolkit="http://schemas.microsoft.com/wpf/2008/toolkit"
* Use controls
  < toolkit:DataGrid > ... < /toolkit:DataGrid > 

## REPO STRUCTURE

I'd like to document this, but I don't really understand it since
it is just a copy from wpftoolkit source release.


## API DOCUMENTATION

See the xml build artifact and the wpf.codeplex.com documentation.

## CONTRIBUTE

If you'd like to hack on wpftoolkit or have your own bugfixes, start by forking my repo on GitHub:

http://github.com/jrwren/wpftoolkit

The best way to get
your changes merged back into core is as follows:

1. Clone down your fork
1. Create a thoughtfully named topic branch to contain your change
1. Hack away
1. If you are adding new functionality, document it in the README.md
1. Do not change the version number, I will do that on my end
1. If necessary, rebase your commits into logical chunks, without errors
1. Push the branch up to GitHub
1. Send a pull request to the project.