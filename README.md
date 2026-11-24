# gradient-generator

{
    "test":  "Caveman on a real project: Architecture Analysis, with vs without Caveman",
    "date":  "2026-11-24",
    "model":  "claude-opus-5",
    "claudeCode":  "2.1.331 (Claude Code)",
    "project":  {
                    "files":  1156,
                    "topExtensions":  [
                                          ".tsx",
                                          ".ts",
                                          ".sql",
                                          ".yaml",
                                          ".md",
                                          ".json"
                                      ]
                },
    "runsPerSide":  2,
    "note":  "Costs are Claude Code\u0027s API list-price estimates, not billed on a subscription. Quality: one blind rating by claude-opus-5 without a reference answer.",
    "runs":  [
                 {
                     "run":  "baseline-1",
                     "profile":  "baseline",
                     "ok":  true,
                     "cavemanActive":  false,
                     "totalTokens":  1704385,
                     "outputTokens":  17562,
                     "costUsd":  2.2381,
                     "seconds":  239.5,
                     "answerWords":  3362,
                     "quality":  94
                 },
                 {
                     "run":  "caveman-1",
                     "profile":  "caveman",
                     "ok":  true,
                     "cavemanActive":  true,
                     "totalTokens":  692733,
                     "outputTokens":  11855,
                     "costUsd":  1.3571,
                     "seconds":  165.9,
                     "answerWords":  1902,
                     "quality":  84
                 },
                 {
                     "run":  "caveman-2",
                     "profile":  "caveman",
                     "ok":  true,
                     "cavemanActive":  true,
                     "totalTokens":  1056697,
                     "outputTokens":  12452,
                     "costUsd":  1.5324,
                     "seconds":  169.9,
                     "answerWords":  2149,
                     "quality":  87
                 },
                 {
                     "run":  "baseline-2",
                     "profile":  "baseline",
                     "ok":  true,
                     "cavemanActive":  false,
                     "totalTokens":  1613075,
                     "outputTokens":  21604,
                     "costUsd":  2.1775,
                     "seconds":  286,
                     "answerWords":  3259,
                     "quality":  89
                 }
             ],
    "summary":  {
                    "totalTokens":  {
                                        "withoutCaveman":  1658730,
                                        "withCaveman":  874715,
                                        "changePercent":  -47.3
                                    },
                    "outputTokens":  {
                                         "withoutCaveman":  19583,
                                         "withCaveman":  12153.5,
                                         "changePercent":  -37.9
                                     },
                    "costUsd":  {
                                    "withoutCaveman":  2.2078,
                                    "withCaveman":  1.44475,
                                    "changePercent":  -34.6
                                },
                    "seconds":  {
                                    "withoutCaveman":  262.75,
                                    "withCaveman":  167.9,
                                    "changePercent":  -36.1
                                },
                    "quality":  {
                                    "withoutCaveman":  91.5,
                                    "withCaveman":  85.5,
                                    "changePercent":  -6.6
                                },
                    "answerWords":  {
                                        "withoutCaveman":  3310.5,
                                        "withCaveman":  2025.5,
                                        "changePercent":  -38.8
                                    }
                }
}
