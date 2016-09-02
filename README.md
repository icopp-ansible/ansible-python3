# ansible-python3

Install Python 3 via Homebrew. Does nothing on non-macOS platforms.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew) (included as repository dependency)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.python3
```

## License

MIT
