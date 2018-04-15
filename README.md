# My Ruby Koans Solution
This is the solution for the Ruby Koans available at http://rubykoans.com.

## How to run tests in vim
I'm using `vim` throughout this course, and a very easy way to running tests (supposing you're in the `koans/` directory) is this:

`:map ,t :w \| :!ruby path_to_enlightenment.rb<CR>`

That way, you can quickly answer the `assert_*` and then just hit `,t` and see if the answer is correct!

