---
title: Chapter Title Here
description: Chapter description goes here.
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills:
  - 2
```

This is an example exercise. etyrtvtw4yvyeryvrtyyhge

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Insert exercise title here

```yaml
type: VideoExercise
key: 9f1a9f523f
xp: 50
```

`@projector_key`
85da9d97646e50e1402822edd06abd64

---

## Insert exercise title here

```yaml
type: NormalExercise
key: 182df9c3b5
xp: 100
```

<!-- Guidelines for contexts: https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->
khvfxxbjbgg ae rgetrtsgserg erg segerg erg seg

`@instructions`
<!-- Guidelines for instructions https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->
- Instruction 1
- Instruction 2
- Instruction 3

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
selected_answer = 1
```

`@sct`
```{python}
# Examples of good success messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.
msg = "Have you correctly initialized `my_list`?"
Ex().check_correct(
    check_object('my_list').has_equal_value(),
    multi(
        # check initialization: [] or list()
        check_or(
            has_equal_ast(code = "[]", incorrect_msg = msg),
            check_function('list')
        ),
        check_for_loop().multi(
            check_iter().has_equal_value(),
            check_body().check_if_else().multi(
                check_test().multi(
                    set_context(2).has_equal_value(),
                    set_context(3).has_equal_value()
                ),
                check_body().set_context(3).\
                    set_env(my_list = [0]).\
                    has_equal_value(name = 'my_list')
            )
        )
    )
)
```

---

## Insert exercise title here

```yaml
type: PureMultipleChoiceExercise
key: 44a2a7eb86
xp: 50
```

Markdown, *under* each other
![Heatmap](https://assets.datacamp.com/production/repositories/5634/datasets/e6986ae6c567536983298eaf3a1f4b3e8d8a2cac/heatmap.png)
![Heatmap](https://assets.datacamp.com/production/repositories/5634/datasets/e6986ae6c567536983298eaf3a1f4b3e8d8a2cac/heatmap.png)
Markdown, *next to* each other
![Heatmap](https://assets.datacamp.com/production/repositories/5634/datasets/e6986ae6c567536983298eaf3a1f4b3e8d8a2cac/heatmap.png) ![Heatmap](https://assets.datacamp.com/production/repositories/5634/datasets/e6986ae6c567536983298eaf3a1f4b3e8d8a2cac/heatmap.png)
HTML, *under* each other
<img src="https://assets.datacamp.com/production/repositories/5634/datasets/e6986ae6c567536983298eaf3a1f4b3e8d8a2cac/heatmap.png">
<img src="https://assets.datacamp.com/production/repositories/5634/datasets/e6986ae6c567536983298eaf3a1f4b3e8d8a2cac/heatmap.png">
HTML, *next to* each other
<img src="https://assets.datacamp.com/production/repositories/5634/datasets/e6986ae6c567536983298eaf3a1f4b3e8d8a2cac/heatmap.png" > <img src="https://assets.datacamp.com/production/repositories/5634/datasets/e6986ae6c567536983298eaf3a1f4b3e8d8a2cac/heatmap.png" >

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@possible_answers`
- [Correct answer 1]
- Wrong answer 2
- Wrong answer 3

`@feedback`
<!-- Examples of good feedback messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.  -->
- Perfect!
- Error message answer 2
- Error message answer 3

---

## Insert exercise title here

```yaml
type: VideoExercise
key: abce72ebef
xp: 50
```

`@projector_key`
bff202aadb195f0bd1ef25dfd7dcc1e3
