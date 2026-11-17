==============================================================
  CHRISTIAN APOLOGETICS ASKLO BOT
  Coded in Rust. Created by SodaDaPimp - Christian Apologetics Scholar
  Copyright 2026 Christian Apologetics Bot https://www.youtube.com/watch?v=aowWP99zlDI
==============================================================

WHAT IT DOES
------------
People in your Paltalk chat room type a command, and the bot answers
them in the room (or by private whisper):

   !asklo <question>        Ask Lo (the AI in the Logetics app) a question
                            about Christianity, the Bible, history or
                            philosophy.  "!ask" works too.
   !verse John 3:16         One verse        (also ranges: Romans 8:28-30)
   !study Psalm 23          A whole chapter
   !verse John 3:16 nkjv    Pick the Bible for one lookup
   !bibles                  List the Bibles available
   !bible kjv               Choose your own Bible (remembered)
   !verse Quran 2:255       Check a verse in the Quran (Pickthall)
   !verse Genesis 1:1 tanakh   The Jewish Bible (JPS 1917)
   !commands                Show everyone the full command list

Answers are posted one request at a time, in a first-come line, with a
cooldown per person so the room is never flooded.


WHAT YOU NEED (all free)
------------------------
 1. A Windows 10 or 11 PC.
 2. BlueStacks 5 (the Android emulator) from bluestacks.com
 3. The Logetics app installed inside BlueStacks and signed in to
    your own account.  The bot uses YOUR Logetics - nothing is shared.
 4. The Paltalk app for Windows, signed in, with your chat room open.

The program is one file: ChristianApologeticsAskLoBot.exe
No installer.  Put it in its own folder (for example
C:\AskLoBot) - it saves its settings next to itself.


ONE-TIME SETUP
--------------
 1. BlueStacks:  Settings -> Advanced -> Android Debug Bridge (ADB): ON.
 2. In BlueStacks open Logetics, sign in, and open the ASK LO tab once
    to make sure it works.  Leave BlueStacks running.
 3. In Paltalk, sign in with the account the bot will speak as and OPEN
    THE ROOM.  Keep the room window open - not minimized.
 4. Double-click ChristianApologeticsAskLoBot.exe.
 5. Settings tab -> "Find Paltalk windows" -> choose your room in
    "Room window".  (Or just type part of the room's name.)
 6. Settings tab -> BlueStacks -> "Auto-detect ADB and port".
 7. Tools tab -> "Test connection", then "Read the chat".
    You should see the room's messages listed.
    The "Ask Lo" button shows Lo's answer without posting anything.
 8. Home tab -> START BOT.  Done!

Tip: tick "Test mode" the first time.  The bot then only logs what it
WOULD answer and posts nothing, so you can check it safely.
Settings also lets you block people, change the command words and the
waiting times.


WHISPERS
--------
 * "Whisper only mode" (Home tab): answers go to the person by private
   whisper instead of filling the room.
 * Anyone can whisper the bot:  type /  pick the bot's name, then
   !asklo your question   - the answer always comes back by whisper.
 * Note: Paltalk does not let an account whisper to itself, so test
   whispers from a second account.


GOOD TO KNOW
------------
 * The bot types into Paltalk like a person would, so it briefly takes
   the keyboard when posting.  It works best on a PC you are not typing
   on while it runs (or a spare PC / second Windows user).
 * Keep the Paltalk room window tall, at the newest messages, and not
   minimized.  BlueStacks may be covered but must stay running.
 * Lo takes a while to answer (often 20-30 seconds) - that is normal.
   People who ask meanwhile are told their place in line.
 * Questions are passed to Lo as plain English text.
 * Make sure the room owner and Paltalk's rules allow chat bots.
 * Bible versions available depend on what your Logetics app is
   licensed for.  The Quran (Pickthall, 1930) and the Tanakh
   (JPS 1917) are public-domain texts built into the program.


FILES THE PROGRAM CREATES (next to the .exe)
--------------------------------------------
   bot_config.ini      your settings (a backup .bak is kept)
   bot_stats.ini       the all-time answer count
   bible_choices.ini   each person's chosen Bible
   bot_log.txt         activity log


IF SOMETHING DOES NOT WORK
--------------------------
 * "Read the chat" shows nothing: use Tools -> Diagnostics ->
   "Inspect Paltalk window".  It saves paltalk_dump.txt next to the
   program - send that file (and the log) to the author.
 * Nothing happens in BlueStacks: check that ADB is ON, Logetics is
   signed in, then press Tools -> "Test connection".
 * Windows SmartScreen says "Windows protected your PC": this program
   is new and not code-signed.  Click "More info" -> "Run anyway".
 * Antivirus flags it: programs that press keys and read windows can
   trigger false alarms.  Add the folder to your antivirus exclusions.
   You can check the download against SHA256.txt:
      PowerShell:  Get-FileHash .\ChristianApologeticsAskLoBot.exe


ABOUT
-----
Christian Apologetics AskLo Bot - Coded in Rust, created by SodaDaPimp,
Christian Apologetics Scholar: combining academic training with a
reasoned defense of the Christian faith across history and philosophy.

This is an independent project.  It is not made by, affiliated with or
endorsed by Paltalk, Logetics or BlueStacks; those names belong to
their owners.  Provided free, as-is, without warranty.  Please do not
re-sell it or pass off modified copies as the original.

Built with open-source software, including the Rust language, the egui
interface library and the Hack font (MIT / Apache-2.0 / Bitstream Vera
licences).  Their licence notices are included inside the program.

Copyright 2026 Christian Apologetics Bot.  Coded in Rust.
Created By SodaDaPimp.
