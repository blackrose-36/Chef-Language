# Addition Cake 🍰

A tiny program written in [Chef](https://www.dangermouse.net/esoteric/chef.html), the esoteric programming language where programs look like cooking recipes.

This recipe adds two numbers (2 + 3) and outputs the result.

## The Code

```
Addition Cake.

Ingredients.
2 g sugar
3 g flour

Method.
Put sugar into the mixing bowl.
Add flour to the mixing bowl.
Pour contents of the mixing bowl into the baking dish.

Serves 1.
```

## How It Works

| Step | What it does |
|------|--------------|
| `2 g sugar` / `3 g flour` | Declares two dry ingredients, which hold the numbers 2 and 3. |
| `Put sugar into the mixing bowl.` | Pushes 2 onto the mixing bowl stack. |
| `Add flour to the mixing bowl.` | Adds 3 to the top value of the stack (2 + 3 = 5). |
| `Pour contents of the mixing bowl into the baking dish.` | Moves the stack into the baking dish. |
| `Serves 1.` | Outputs the contents of the first baking dish. |

## Expected Output

```
5
```

## Running the Program

1. Save the recipe as `addition_cake.chef`.
2. Run it with any Chef interpreter. For example, with Perl's [Acme::Chef](https://metacpan.org/pod/Acme::Chef):

```bash
chef.pl addition_cake.chef
```

## About Chef

Chef was designed by David Morgan-Mar. Programs are written as recipes: ingredients are variables, the mixing bowl and baking dish are stacks, and the method steps are instructions.

## License

Free to use, modify, and share.
