# homebrew-sshpass

sshpass formula for Homebrew.

Homebrew maintainers reject adding sshpass for security reasons, but some users need this. For example ansible would use this.

Install in one step:
```bash
brew install marthydavid/sshpass/sshpass 
```
Or via adding tap manually
```bash
brew tap marthydavid/sshpass
brew install sshpass
```

Or install via URL (which will not receive updates):

```bash
brew install https://raw.githubusercontent.com/marthydavid/homebrew-sshpass/main/sshpass.rb
```
