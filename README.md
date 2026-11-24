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
    "runsPerSide":  5,
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
                     "quality":  83
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
                     "quality":  92
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
                     "quality":  92
                 },
                 {
                     "run":  "baseline-3",
                     "profile":  "baseline",
                     "ok":  true,
                     "cavemanActive":  false,
                     "totalTokens":  1491658,
                     "outputTokens":  18607,
                     "costUsd":  1.9789,
                     "seconds":  256,
                     "answerWords":  3944,
                     "quality":  87
                 },
                 {
                     "run":  "caveman-3",
                     "profile":  "caveman",
                     "ok":  true,
                     "cavemanActive":  true,
                     "totalTokens":  932380,
                     "outputTokens":  13960,
                     "costUsd":  1.4638,
                     "seconds":  195,
                     "answerWords":  1822,
                     "quality":  79
                 },
                 {
                     "run":  "caveman-4",
                     "profile":  "caveman",
                     "ok":  true,
                     "cavemanActive":  true,
                     "totalTokens":  570856,
                     "outputTokens":  10510,
                     "costUsd":  1.1798,
                     "seconds":  145.5,
                     "answerWords":  1627,
                     "quality":  88
                 },
                 {
                     "run":  "baseline-4",
                     "profile":  "baseline",
                     "ok":  true,
                     "cavemanActive":  false,
                     "totalTokens":  1544102,
                     "outputTokens":  16855,
                     "costUsd":  2.1701,
                     "seconds":  227.3,
                     "answerWords":  2850,
                     "quality":  91
                 },
                 {
                     "run":  "baseline-5",
                     "profile":  "baseline",
                     "ok":  true,
                     "cavemanActive":  false,
                     "totalTokens":  1340541,
                     "outputTokens":  16844,
                     "costUsd":  1.9589,
                     "seconds":  226,
                     "answerWords":  3284,
                     "quality":  86
                 },
                 {
                     "run":  "caveman-5",
                     "profile":  "caveman",
                     "ok":  true,
                     "cavemanActive":  true,
                     "totalTokens":  542757,
                     "outputTokens":  11357,
                     "costUsd":  1.196,
                     "seconds":  152.5,
                     "answerWords":  1982,
                     "quality":  84
                 }
             ],
    "summary":  {
                    "totalTokens":  {
                                        "withoutCaveman":  1544102,
                                        "withCaveman":  692733,
                                        "changePercent":  -55.1
                                    },
                    "outputTokens":  {
                                         "withoutCaveman":  17562,
                                         "withCaveman":  11855,
                                         "changePercent":  -32.5
                                     },
                    "costUsd":  {
                                    "withoutCaveman":  2.1701,
                                    "withCaveman":  1.3571,
                                    "changePercent":  -37.5
                                },
                    "seconds":  {
                                    "withoutCaveman":  239.5,
                                    "withCaveman":  165.9,
                                    "changePercent":  -30.7
                                },
                    "quality":  {
                                    "withoutCaveman":  91,
                                    "withCaveman":  84,
                                    "changePercent":  -7.7
                                },
                    "answerWords":  {
                                        "withoutCaveman":  3284,
                                        "withCaveman":  1902,
                                        "changePercent":  -42.1
                                    }
                }
}

