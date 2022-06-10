# moe-betta
A simple yet aggressive SC2 AI that will soon be attempting to climb the AI ladder and will be playable in realtime for practicing agaisnt optimal aggressive proxy pushes.
The current strat is a proxy Barracks  Marine push followed up by Marine + Thor All-in.
This is still in early form and will be updated heavily moving forward.


Current goals:
1) Create a function that gets called inside on_start() that sends 2 workers to proxy location. (x)
2) Create a filter to target workers closest to proxy location and set those workers to build the proxy barracks. (Distribute workers function makes this tricky...)
3) Implement mutliple proxy locations using an array to enable random indexing to find a random proxy location each game.
4) Implement a better Marine/Thor micro model that can handle game-deciding actions reliably.(lol.)
5) Implement building a bunker during inital Marine push.
6) Implement Marine AI to utilize bunker.
7) Convert to a Real Time AI that is playable locally.


How to complile and review current implementation (only on Windows):

1) Install Starcraft 2:
            https://starcraft2.com/en-us/
2) Install Rust:
            https://www.rust-lang.org/tools/install
3) Install the C++ build tools:
            https://visualstudio.microsoft.com/visual-cpp-build-tools/
4) Download 2021Season2Ladder.zip Map files and extract into C:\users\\*username*\program files (x86)\Starcraft II\Maps
            https://wiki.sc2ai.net/Ladder_Maps
5) Install Git for Windows: 
            https://git-scm.com/download/win
6) Clone repo:
            git clone https://github.com/Garrett7k/moe-betta.git
7) CD moe-betta
8) Cargo run

