# Overview
This project represents a collection of different PowerShell scripts I've written to solve various problems.  It didn't seem to make sense to create new projects for each one, so I've included all of them together into one, miscellaneous project.  I'll be adding more scripts over time, more than likely.

## organize_mp3s.ps1
This script catalogs my entire digitized music catalog and then allows me copy certain files over to a flash drive by whatever selection criteria I choose, such as genre.  This script has no third party dependencies: I use the shell.application COM object to gather ID3 tag information on all my MP3 files (not for a lack of trying: I tried to use several of the open source .NET ID3 libraries out on github, nuget, and sourceforge, but could get none of them to work).
