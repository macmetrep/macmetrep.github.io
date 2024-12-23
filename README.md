# macmetrep.github.io

static hosting

* index: coaching upsell

## recommendations to make:

```swift
 static let dietRecos: [TeaserDiets: Recommendation] = [
    .carbo: Recommendation(
      title: "Carbohydrate-Based Diet",
      description: "We recommend a carbohydrate-based diet to help you lose weight.",
      priority: .high,
      icon: .sfSymbol("carrot")
    ),
    .fatoKeto: Recommendation(
      title: "Ketogenic Diet",
      description:
        "A high-fat, low-carb approach that may help with your specific metabolic needs.",
      priority: .high,
      icon: .sfSymbol("leaf")
    ),
    .proteinFiberSatiation: Recommendation(
      title: "High Protein & Fiber Diet",
      description:
        "Focus on protein and fiber-rich foods to improve satiety and support your weight loss goals.",
      priority: .high,
      icon: .sfSymbol("figure.strengthtraining.traditional")
    ),
    .highStarch: Recommendation(
      title: "High Starch Diet",
      description:
        "A diet rich in complex carbohydrates to support your energy needs and metabolism.",
      priority: .high,
      icon: .sfSymbol("wheat")
    ),
    .lowCarb: Recommendation(
      title: "Low Carb Diet",
      description:
        "Reduce carbohydrate intake while maintaining adequate protein and healthy fats.",
      priority: .high,
      icon: .sfSymbol("leaf.fill")
    ),
    .fitHighStarch: Recommendation(
      title: "Athletic High Starch Diet",
      description:
        "Optimized for active individuals, this diet provides plenty of energy for workouts while supporting recovery.",
      priority: .high,
      icon: .sfSymbol("figure.run")
    ),
    .fitLowCarb: Recommendation(
      title: "Athletic Low Carb Diet",
      description:
        "A modified low-carb approach that accounts for your training needs while maintaining metabolic flexibility.",
      priority: .high,
      icon: .sfSymbol("figure.hiking")
    ),
    .specialGutRepair: Recommendation(
      title: "Gut Repair Protocol",
      description:
        "A specialized diet focused on healing and supporting optimal gut function while achieving your weight goals.",
      priority: .high,
      icon: .sfSymbol("stomach")
    ),
  ]

  static let possibleRecos: [String: Recommendation] = [
    "gutSupportAlternative": Recommendation(
      title: "Consider a gut repair diet",
      description:
        "Even though your goal is to lose weight, you may want to consider a gut repair diet to support your as your first target.  Even if you don't think you have gut issues, you have some issues that are linked with gut issues.  With a healthy gut, you will probably lose weight much easier, and might lose weight as a side effect.",
      priority: .high,
      icon: .emoji("🍲")
    ),
    "collagenForRecovery": Recommendation(
      title: "Collagen for Strength Recovery",
      description:
        "You have a long recovery time for your strength workouts.  Supplementing with collagen daily might speed up your recovery time.",
      priority: .low,
      icon: .emoji("💪")
    ),
    "proteinAddition": Recommendation(
      title: "Add Protein to Your Recommended Diet",
      description:
        "Since you strength train more than twice a week, you will want to add more protein to the diets we are recommending.",
      priority: .medium,
      icon: .emoji("🥩")
    ),
    "circadianManagement": Recommendation(
      title: "Circadian Stimulus Management",
      description:
        "We have noted some sleep issues.  Managing your light stimulus thoughout the day might help you sleep better.",
      priority: .high,
      icon: .sfSymbol("moon.stars")
    ),
    "liverSupport": Recommendation(
      title: "Liver Health Detox Program",
      description:
        "We have noted some liver health issues.  We recommend a liver health detox program to help you improve your liver health in addition to your weight loss diet.",
      priority: .medium,
      icon: .sfSymbol("heart.text.square")
    ),
    "cholineTest": Recommendation(
      title: "Choline Experiment",
      description:
        "Because you love egg yolks, we suspect you have a higher than typical need for choline.  We recommend eating 9 egg yolks (or whole eggs) daily for 4 days and see if you feel better.",
      priority: .low,
      icon: .sfSymbol("egg")
    ),
    "oystersTest": Recommendation(
      title: "Mineral Rich Foods Experiment",
      description:
        "We have noted some mineral deficiencies.  We recommend eating oysters and mineral-rich foods for 4 days and see if you feel better.",
      priority: .low,
      icon: .emoji("🦪")
    ),
    "omega3FishTest": Recommendation(
      title: "Omega-3 Foods Experiment",
      description:
        "We have noted some omega-3 deficiencies.  We recommend eating more omega-3 rich fish for 4 days and see if you feel better.",
      priority: .low,
      icon: .emoji("🐟")
    ),
    "boneBrothTest": Recommendation(
      title: "Bone Broth Experiment",
      description:
        "We have noted some desires for glyicine.  We recommend eating bone broth for 4 days and see if you feel better.",
      priority: .low,
      icon: .emoji("🥣")
    ),
  ]
```