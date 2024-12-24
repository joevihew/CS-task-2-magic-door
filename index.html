<?php
// Start the session to track the user's choices
session_start();

// Reset the game if the user clicks "Restart"
if (isset($_GET['restart'])) {
    session_destroy();
    header("Location: index.php");
    exit;
}

// Define the story paths
$story = [
    'start' => [
        'text' => 'Today you are a Pokémon trainer! What Pokémon would you like to choose as your starter? <br><img src="https://i.ytimg.com/vi/942ZgSmTz6M/maxresdefault.jpg" style="width: 950px;">',
        'choices' => [
            'Bul' => '1',
            'Cha' => '2',
            'Squ' => '3',
        ]
    ],
    'Bul' => [
        'text' => 'Good job! You choose Bulbasaur. Are you sure you want Bulbasaur? <br><img src="https://static1.thegamerimages.com/wordpress/wp-content/uploads/2021/10/Bulbasaur.jpg" style="width: 950px;">',
        'choices' => [
            'Yes_Bul' => 'Yes, I want Bulbasaur.',
            'No' => 'No, I changed my mind.',
        ]
    ],
    'Cha' => [
        'text' => 'Good job! You choose Charmander. Are you sure you want Charmander? <br><img src="https://www.dexerto.com/cdn-image/wp-content/uploads/2023/11/15/Pokemon-TCG-Charmander.jpg?width=1200&quality=60&format=auto" style="width: 950px;">',
        'choices' => [
            'Yes_Cha' => 'Yes, I want Charmander.',
            'No' => 'No, I changed my mind.',
        ]
    ],
    'Squ' => [
        'text' => 'Good job! You choose Squirtle. Are you sure you want Squirtle?<br><img src="https://www.thefactsite.com/wp-content/uploads/2023/08/squirtle-facts.jpg" style="width: 950px;">',
        'choices' => [
            'Yes_Squ' => 'Yes, I want Squirtle.',
            'No' => 'No, I changed my mind.',
        ]
    ],
    'No' => [
        'text' => 'No worries! Choose your starter again.<br><img src="https://i.pinimg.com/736x/3c/a0/8b/3ca08beec594897f38f250e53d42aeb6.jpg" style="width: 950px;">',
        'choices' => [
            'Bul' => 'Bulbasaur',
            'Cha' => 'Charmander',
            'Squ' => 'Squirtle',
        ]
    ],
    'Yes_Bul' => [
        'text' => 'You are now officially a trainer with Bulbasaur! Which route would you like to take? <br><img src="https://preview.redd.it/drew-myself-and-the-best-starter-bulbasaur-not-biased-at-v0-1b74vcd75jca1.png" style="width: 950px;">',
        'choices' => [
            'Route1' => 'Route 1',
            'Route2' => 'Route 2',
        ]
    ],
    'Yes_Cha' => [
        'text' => 'You are now officially a trainer with Charmander! Which route would you like to take? <br><img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/f2b59c5f-5133-469e-908a-9c0b95c6aa62/dg6os2s-4e29b552-36c1-4748-956c-d2f168f60a60.jpg/v1/fill/w_1024,h_1449,q_75,strp/fire_trainer_and_charmander_by_tyartist25_dg6os2s-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2YyYjU5YzVmLTUxMzMtNDY5ZS05MDhhLTljMGI5NWM2YWE2MlwvZGc2b3Mycy00ZTI5YjU1Mi0zNmMxLTQ3NDgtOTU2Yy1kMmYxNjhmNjBhNjAuanBnIiwiaGVpZ2h0IjoiPD0xNDQ5Iiwid2lkdGgiOiI8PTEwMjQifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uud2F0ZXJtYXJrIl0sIndtayI6eyJwYXRoIjoiXC93bVwvZjJiNTljNWYtNTEzMy00NjllLTkwOGEtOWMwYjk1YzZhYTYyXC90eWFydGlzdDI1LTQucG5nIiwib3BhY2l0eSI6OTUsInByb3BvcnRpb25zIjowLjQ1LCJncmF2aXR5IjoiY2VudGVyIn19.XaV4ZkTeEFH1o3k6EumjJA8e5l6PZ1OZ0Jr8Sn0WiH4" style="width: 950px;">',
        'choices' => [
            'Route1' => 'Route 1',
            'Route2' => 'Route 2',
        ]
    ],
    'Yes_Squ' => [
        'text' => 'You are now officially a trainer with Squirtle! Which route would you like to take? <br><img src="https://i.pinimg.com/474x/07/df/73/07df73e1c653b04600591470c4193739.jpg" style="width: 950px;">',
        'choices' => [
            'Route1' => 'Route 1',
            'Route2' => 'Route 2',
        ]
    ],
    'Route1' => [
        'text' => 'You encounter a wild Pidgey. What would you like to do? <br><img src="https://i.pinimg.com/736x/59/fc/da/59fcdae64d666ba265d489e689acb124.jpg" style="width: 950px;">',
        'choices' => [
            'Battle_Pidgey' => 'Battle the Pidgey.',
            'Catch_Pidgey' => 'Try to catch it.',
            'Run_Pidgey' => 'Run away.',
        ]
    ],
    'Battle_Pidgey' => [
        'text' => 'You fought bravely and defeated the Pidgey! What will you do next? <br><img src="https://media.pocketmonsters.net/characters/8/839.png" style="width: 950px;">',
        'choices' => [
            'Continue' => 'Continue your journey.',
            'Rest' => 'Take a rest.',
        ]
    ],
    'Catch_Pidgey' => [
        'text' => 'You successfully caught the Pidgey! What will you do next? <br><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRu67JOBxsX4fuc1q73mJDbB2K4OM52k0_TmaKt6j7ivrlkR73kNADd3Wxmd2Y8KlZi-g0&usqp=CAU" style="width: 950px;">',
        'choices' => [
            'Continue' => 'Continue your journey.',
            'Check_Pidgey' => 'Check your new Pokémon.',
        ]
    ],
    'Run_Pidgey' => [
        'text' => 'You ran away safely. What will you do next? <br><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-c5jz-k5x2aCR8RyZwSy0BmXhaRGAMLLqng&s" style="width: 950px;">',
        'choices' => [
            'Continue' => 'Continue your journey.',
            'Explore' => 'Explore the area.',
        ]
    ],
    'Route2' => [
        'text' => 'You arrive at Route 2, known for its mysterious items. You sense something special here. What will you do? <br><img src="https://img.gamewith.net/article/thumbnail/rectangle/14035.png" style="width: 950px;">',
        'choices' => [
            'Search_Item' => 'Search for a mysterious item.',
            'Continue' => 'Continue to explore.',
            'Ask_Trainer' => 'Ask a nearby trainer for advice.',
        ]
    ],
    'Search_Item' => [
        'text' => 'You found a glowing item hidden in the bushes! It’s a legendary item that can help you catch legendary Pokémon! What will you do? <br><img src="https://assetsio.gnwcdn.com/Pokemon-Go-Master-Ball-Header.jpg?width=1200&height=1200&fit=crop&quality=100&format=png&enable=upscale&auto=webp" style="width: 950px;">',
        'choices' => [
            'Take_Item' => 'Take the Legendary Item.',
            'Leave_Item' => 'Leave the item.',
            'Inspect_Item' => 'Inspect the item closely.',
        ]
    ],
    'Take_Item' => [
        'text' => 'You took the Master Ball! Now you can catch legendary Pokémon. What will you do next? <br><img src="https://archives.bulbagarden.net/media/upload/thumb/3/37/Master_Ball_anime.png/250px-Master_Ball_anime.png" style="width: 950px;">',
        'choices' => [
            'Route3' => 'Head to Route 3 to search for legendary Pokémon.',
            'End' => 'End your adventure.',
        ]
    ],
    'Inspect_Item' => [
        'text' => 'Upon closer inspection, you find the item has mysterious engravings. It’s more powerful than you imagined! What will you do? <br><img src="https://tagn.wordpress.com/wp-content/uploads/2023/06/pokemongomasterball-1.png" style="width: 950px;">',
        'choices' => [
            'Take_Item' => 'Take the Legendary Item.',
            'Leave_Item' => 'Leave the item.',
        ]
    ],
    'Leave_Item' => [
        'text' => 'You decided to leave the item behind. What will you do next? <br><img src="https://example.com/leave.png" style="width: 950px;">',
        'choices' => [
            'End' => 'End your adventure.',
        ]
    ],
    'Route3' => [
        'text' => 'You arrive at Route 3, where rumors say a legendary Pokémon appears. Will you use the Legendary Item to catch it? <br><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRp7Pr68kdN-zI_eNZ6vMP61nICKIlzRoup7g&s" style="width: 950px;">',
        'choices' => [
            'Use_Item' => 'Use the Legendary Item to catch the Pokémon.',
            'Search_Area' => 'Search the area for clues.',
            'Leave' => 'Leave the area.',
        ]
    ],
    'Search_Area' => [
        'text' => 'You searched the area and found signs of the legendary Pokémon nearby! What will you do? <br><img src="https://t4.ftcdn.net/jpg/04/76/01/53/360_F_476015389_JUIS5lfBRK2nrzA0voJJVtRMVeqg5Wrm.jpg" style="width: 950px;">',
        'choices' => [
            'Use_Item' => 'Use the Legendary Item to catch the Pokémon.',
            'Wait' => 'Wait patiently for it to appear.',
        ]
    ],
    'Wait' => [
        'text' => 'You waited patiently, and the legendary Pokémon appeared! What will you do? <br><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQItI3y3fhSu6n_N3odQBSSeE1E1L4rjSFAA&s" style="width: 950px;">',
        'choices' => [
            'Use_Item' => 'Use the Legendary Item to catch it.',
            'Battle' => 'Battle it with your Pokémon.',
        ]
    ],
    'Battle' => [
        'text' => 'You battled fiercely and managed to weaken the legendary Pokémon! Will you attempt to catch it? <br><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ8WlmvYZg0RlqylDkFEl_s4fMk0VXV9pU6gg&s" style="width: 950px;">',
        'choices' => [
            'Catch_Legendary' => 'Attempt to catch it.',
            'Run_Legendary' => 'Run away.',
        ]
    ],
    'Catch_Legendary' => [
        'text' => 'You caught the legendary Pokémon after a tough battle! Congratulations, you are now a Pokémon Master! <br><img src="https://example.com/catch.png" style="width: 950px;">',
        'choices' => [
            'End' => 'End your adventure.',
        ]
    ],
    'Run_Legendary' => [
        'text' => 'You ran away from the legendary Pokémon. Your journey continues. <br><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZww3xOPSCezRsz6npt69PxFNN4YdE5Ay-xQ&s" style="width: 950px;">',
        'choices' => [
            'Continue' => 'Continue your journey.',
        ]
    ],
    'Use_Item' => [
        'text' => 'You used the Master Ball and successfully caught the legendary Pokémon! Congratulations, you are now a Pokémon Master! <br><img src="https://i.redd.it/l78iipyoelja1.jpg" style="width: 950px;">',
        'choices' => [
            'End' => 'End your adventure.',
        ]
    ],
    'Leave' => [
        'text' => 'You decided to leave the area. Your journey continues elsewhere. <br><img src="https://example.com/leave_area.png" style="width: 950px;">',
        'choices' => [
            'Continue' => 'Continue your journey.',
        ]
    ],
    'Continue' => [
        'text' => 'You decided to continue your journey. Where will you go next? <br><img src="https://www.serebii.net/pokearth/maps/galar/3.jpg" style="width: 950px;">',
        'choices' => [
            'Route2' => 'Continue to Route 2.',
            'Route3' => 'Continue to Route 3.',
        ]
    ],
    'End' => [
        'text' => 'Thank you for playing the Pokemon Adventure! Your journey ends here. Remember, every end is a new beginning! <br><img src="https://example.com/end.png" style="width: 950px;">',
        'choices' => []
    ],
    'Ask_Trainer' => [
        'text' => 'The trainer rob you and you died. What will you do? <br><img src="https://static1.cbrimages.com/wordpress/wp-content/uploads/2021/05/Team-Rocket.jpg" style="width: 950px;">',
        'choices' => [
            'start' => 'End your adventure.',
        ]
    ],
    'Check_Pidgey' => [
        'text' => 'Your Pidgey is healthy and ready for battle! What will you do next? <br><img src="https://example.com/check_pidgey.png" style="width: 950px;">',
        'choices' => [
            'Route2' => 'Continue to Route 2.',
            'Explore' => 'Explore more areas.',
        ]
    ],
    'Explore' => [
        'text' => 'You found a hidden path that leads to a secret meadow! What will you do? <br><img src="https://preview.redd.it/spent-around-30-hours-drawing-this-gonna-fill-the-meadow-v0-z5uot9bbpnmb1.png?width=1080&crop=smart&auto=webp&s=aafd0987c2b6bb82b4aae8ccda218f02bef6cfe4" style="width: 950px;">',
        'choices' => [
            'Rest' => 'Rest in the meadow.',
            'Search_Meadow' => 'Search for rare Pokémon.',
        ]
    ],
    'Search_Meadow' => [
        'text' => 'You found a rare Pokémon in the meadow! What will you do? <br><img src="https://pbs.twimg.com/media/FRc5t8IWUAIq2RG.jpg" style="width: 950px;">',
        'choices' => [
            'Catch_Meadow' => 'Try to catch it.',
            'Battle_Meadow' => 'Battle it.',
            'Talk_Meadow' => 'Give him food',
        ]
    ],
    'Catch_Meadow' => [
        'text' => 'You caught the rare Pokémon! It will be a great addition to your team. <br><img src="https://www.dexerto.com/cdn-image/wp-content/uploads/2023/11/14/Poke-Ball-Pokemon-anime.jpg?width=1200&quality=60&format=auto" style="width: 950px;">',
        'choices' => [
            'Continue' => 'Continue your journey.',
        ]
    ],
    'Battle_Meadow' => [
        'text' => 'You battled the rare Pokémon and gained valuable experience! What will you do next? <br><img src="https://preview.redd.it/7-phase-1-for-a-female-shiny-eevee-the-chain-continues-v0-c2umg63877v91.jpg?width=640&crop=smart&auto=webp&s=fc3bafeeeb70f231819a07bd54a233147a64b068" style="width: 950px;">',
        'choices' => [
            'Continue' => 'Continue your journey.',
        ]
    ],
    'Rest' => [
        'text' => 'You had a peaceful rest and feel rejuvenated. What will you do next? <br><img src="https://www.pokemon.com/static-assets/content-assets/cms2/img/video-games/video-games/pokemon_sleep/inline/01.png" style="width: 950px;">',
        'choices' => [
            'Continue' => 'Continue your journey.',
        ]
    ],
    'Talk_Meadow' => [
        'text' => 'The Pokemon suddenly bite you to death. What will you do? <br><img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/27dbbda7-320b-488b-b8cb-6d993296f095/dd8vmtb-ad00229d-3c16-4d5e-882d-ccfaabe018f1.png/v1/fill/w_1280,h_581/shiny_eevee_using_sand_attack_by_transparentjiggly64_dd8vmtb-fullview.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NTgxIiwicGF0aCI6IlwvZlwvMjdkYmJkYTctMzIwYi00ODhiLWI4Y2ItNmQ5OTMyOTZmMDk1XC9kZDh2bXRiLWFkMDAyMjlkLTNjMTYtNGQ1ZS04ODJkLWNjZmFhYmUwMThmMS5wbmciLCJ3aWR0aCI6Ijw9MTI4MCJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.CIeStEnPmag4EFXdZ11OZc2Vw1sJnV8NNG4CB5ZQw5w" style="width: 950px;">',
        'choices' => [
            'start' => 'End your adventure.',
        ]
    ]
];

// Determine the current step
$currentStep = isset($_GET['step']) ? $_GET['step'] : 'start';

// Check if the current step exists in the story array
if (isset($story[$currentStep])) {
    // Get the current story segment
    $currentStory = $story[$currentStep];
} else {
    // Handle the case where the step is invalid
    $currentStory = [
        'text' => 'Invalid step. Returning to the start of the adventure.',
        'choices' => ['start' => 'Go to the start']
    ];
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pokemon Adventure</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Pokemon Adventure</h1>
        <p class="story-text"> <?php echo $currentStory['text']; ?> </p>

        <?php if (!empty($currentStory['choices'])): ?>
            <div class="choices">
                <?php foreach ($currentStory['choices'] as $step => $choice): ?>
                    <a href="?step=<?php echo $step; ?>" class="choice-button"> <?php echo $choice; ?> </a>
                <?php endforeach; ?>
            </div>
        <?php else: ?>
            <a href="?restart=true" class="restart-button">Restart Adventure</a>
        <?php endif; ?>
    </div>
</body>
</html>
