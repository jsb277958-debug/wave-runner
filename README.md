# wave-runner
A fast-paced, neon browser arcade game. Dodge obstacles, collect coins, and survive the grid.

How to Play

    Hold (click, tap, or spacebar) to fly up.

    Release to drop down.

    The controls are simple, but the speed picks up the longer you survive.

Key Features

    Procedural Levels: No two runs are the same. The game generates obstacles on the fly, gradually speeding up as your score climbs. Hitboxes are tuned to be slightly generous, keeping close calls exciting and deaths feeling fair.

    Random Modifiers: Rare events like Slow Motion, Glitch World, Hyper Speed, and Coin Rush trigger randomly during play, shifting the color palette and changing how you navigate the map.

    Coins & Collectibles: Grab floating gold tokens in the corridors to build your bank. Spikes also reward bonus coins when cleanly evaded.

    Leveling & Achievements: Earn XP on every run to level up your profile and unlock new ranks. Complete in-game achievements to earn coin bonuses.

    The Garage: Spend your coins in the shop to unlock 20 different skins, each with its own visual trail style (like neon ribbons, zigzags, or fading glows) and custom particles.

    Run History & Stats: Check your profile to see your lifetime playtime, average dodges per minute, and a detailed log of your last 10 runs.

    Daily Rewards: Claim daily rewards to build up a login streak and score major milestone payouts on Day 7.

Technical Specs (For Devs & Platforms)

    Engine: Pure HTML5 Canvas & Vanilla JavaScript (no external frameworks or libraries).

    Audio: Custom synth sound effects generated live using the browser’s Web Audio API. This keeps the game lightweight with zero loading times [1].

    Responsive Scaling: The camera scale dynamically adjusts on mobile screens, making sure you always have a fair view of upcoming obstacles regardless of your device's aspect ratio [1].

    Saves: High scores, levels, unlocked skins, and run history are saved automatically in your browser using localStorage.
