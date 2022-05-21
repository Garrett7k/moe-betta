# moe-betta
A simple yet aggressive SC2 bot that will soon be attempting to climb the AI ladder and will be playable in realtime.
The current strat is a proxy 3x Barracks followed by Marine push followed up by Thors.
This is still in early form and will be updated heavily moving forward.


Current goals:
1) Create a function that gets called inside on_start() that sends 2 works to proxy location. 
2) Create a filter to target workers closest to proxy location and set those workers to build the proxy barracks. 
3) Implement a better Marine micro model that can handle game-deciding actions reliably.(lol)
4) Convert to a Real Time bot that is playable locally.


How to complile and view current bot (Currently only on Windows):
1) Install Starcraft 2:
            https://starcraft2.com/en-us/
2) Install Rust:
            https://www.rust-lang.org/tools/install
3) Install the C++ build tools:
            https://visualstudio.microsoft.com/visual-cpp-build-tools/
4) Download 2021Season2Ladder.zip Map files and extract into C:\users\\*username*\program files (x86)\Starcraft II\Maps
            https://wiki.sc2ai.net/Ladder_Maps
6) git clone repo:
            https://github.com/Garrett7k/moe-betta.git
6) CD moe-betta
7) cargo run

