My own copy of 7-zip, with a couple of fairly minor tweaks, and a
Visual Studio 2017 solution.

My party, and I don't have to justify myself to anybody ;)

# How to build

1. Load `FM.sln` into Visual Studio 2017.

2. Select solution configuration. `D` vs `R` for debug vs release; `U`
   for Unicode, I think; `32` vs `64` for x86 vs x64. (The names are
   cryptic so they fit in that widget in the toolbar, that seems to be
   wide enough for the word `Release` and no more.)
   
   You don't need to select the solution platform.

3. Compile.

4. Run.

There are unzipped distributions of 7-Zip in the `dist` folder. Each
configuration builds its exe into the appropriate distribution's
folder, so it can find all the distribution files when it's run.

# Changes

- File/folder autocomplete when typing in the address bar

- Address bar dropdown doesn't drop down when focused. Tap Alt+Down if
  you want it

More to come, perhaps, if I get annoyed enough by something...

# Upstream

https://github.com/kornelski/7z
