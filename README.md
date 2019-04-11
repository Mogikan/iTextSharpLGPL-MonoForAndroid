iTextSharpLGPL-Net standard 2.0
========================
This project is taking the last version of iTextSharp which was licenced with LGPL and making it work with Net standard 2.0.
Project is tested on both Android and iOS

Changes to code:
- Added setter to the Chunk Content.  (This was a custom need.) 
- Removed Barcode files.  (iTextSharp-Monotouch did this and I didn't need it, so I removed it just in case.)
- I needed to restore the Resource IDs of everything in iTextSharp/text/pdf/fonts so they started with "iTextSharp.text.pdf.fonts." so that fonts worked.

Licensing
=========
You have three license choices when it comes to iTextSharp: LGPL, AGPL, or a commercial license. The LGPL license is only an option with the older 4.1.6 version (used here). After that version, they switched to a dual AGPL/Commercial.

The short version of the license conditions goes like this. With LGPL you need to publicly release any changes to the library itself (like I have done here) but you don't have to release the projects that link to the library. With the AGPL license, you need to release all your source code publicly. By merely linking their code in your project, your project is now open-source. Paying for a commercial license, however, let's you use their library and not require you to release your source code. Go here to fill out a form, so they can email you the price: http://itextpdf.com/terms-of-use/index.php

If you need a more recent version, you either have to make your project open-source or pay the license fee. 

Links
=====
iTextSharp-LGPL NuGet Package
http://nuget.org/packages/iTextSharp-LGPL

iTextSharp-4.1.6 From GitHub
https://github.com/itextsharper/iTextSharp-4.1.6

iTextSharp
http://itextpdf.com

iTextSharpLGPL-Monotouch is my sister project that does the same thing for MonoTouch
https://github.com/JamieMellway/iTextSharpLGPL-Monotouch

iTextSharpSL-MPL is a similar project that does the same thing for Silverlight
http://itextsharpsl.codeplex.com/

Mono For Androind
http://xamarin.com/android
