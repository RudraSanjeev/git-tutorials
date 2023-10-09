#### Method and Best Practices to see git log:

- **basic or general will log all the log at once**

```git
    git log
```

- **to get specific no of log**

```git
    git log -n 5
```

- **to get result in graphical manner**

```git
    git log --graph
```

- **to see particular log using hash**

```git
    git show <hash_value>
```

- **to filter by author name**

```git
    git log --author= "jogn doe"
```

- **filter by date**

```git
    git log --since="2022-01-02" --until="2023-03-03"
```

- **custom formating (You can customize output using --format option)**

```git
    git log --format="%h %s (%an, %ad)"
```

- - `%h`: Abbreviated commit hash
  - `%s`: Subject (commit message)
  - `%a`n: Author name
  - `%a`d: Author date

- **Paging**

```git
    git log | less
```

- **Alias**

```git
    git config --global alias.lg "log --graph --oneline --all"
```
