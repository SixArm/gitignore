# Test

To test the rules;

```sh
cd test
./test.sh
```


## How it works

Steps:

1. The `test.sh` script runs some test functions that exercise the gitignore rules.

2. The script saves results into the `results` directory, so you can take a look.

3. The script compares various outputs by using `diff $actual $expect`.


## Example directory structure

Example directory structure for the function `test_dot_rules` :

```txt
test
  results
    test_dot_rules
      git_check_ignore
        actual.txt
        expect.txt
      git_status
        actual.txt
        expect.txt
```