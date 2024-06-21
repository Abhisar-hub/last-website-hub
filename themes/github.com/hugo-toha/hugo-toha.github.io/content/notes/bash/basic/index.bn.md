---
menu:
  notes:
    identifier: notes-bash-variables
    name: ভেরিয়েবল
    parent: notes-bash
    weight: 10
title: ব্যাশ ভেরিয়েবল
weight: 210
---

<!-- Variable -->
{{< note title="Variable" >}}

```bash
NAME="John"
echo $NAME
echo "$NAME"
echo "${NAME}
```

{{< /note >}}

<!-- Condition -->
{{< note title="Condition" >}}

```bash
if [[ -z "$string" ]]; then
  echo "String is empty"
elif [[ -n "$string" ]]; then
  echo "String is not empty"
fi
```

{{< /note >}}