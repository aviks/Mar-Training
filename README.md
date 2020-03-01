# Source files for Training

- Running `julia --project build.jl` will
    1. Create a `Notebooks/` directory
    2. Course content in `Courses/` will get converted to notebook (if `.jl` file) or get directly copied.
    3. A specific course can be built by giving it as an argument, e.g. `julia --project build.jl SomeCourse`.

# Tips

- If you're using Plots + GR, add `ENV["GKSwstype"] = "100" #src` to your .jl file.
