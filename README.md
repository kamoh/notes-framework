## Note-Taking Framework

I started using this lightweight daily note-taking framework in 2015, and it's been a helpful way to keep track of things.

## Framework

Each day's notes starts with a timestamp in this format:

```
==========
9/15/23
==========
```

Meetings are noted in this convention:

```
-- meeting name

  - list of internal attendees
  - [if applicable] list of external attendees

  - meeting notes

--
```

Todos that come up are indicated with *:

```
-- meeting name

  - list of internal attendees
  - [if applicable] list of external attendees

  - meeting notes
  - another general meeting note
  * todo item for me to follow up on

--
```

Throughout the day, I try to move any todo items to the proper bucket if it'll take more than 5 minutes to do, or do it immediately if it will take less time, then indicate the resolution with `->`:

```
-- meeting name

  - list of internal attendees
  - [if applicable] list of external attendees

  - meeting notes
  - another general meeting note
  - person: a sentence or specific thought attributed to someone in the call
    - me: something I said to them
    - me thinking: something I though of along this line of thought, but didn't say
  * todo item for me to follow up on
    -> opened jira ticket for this
  * todo item for me to do right now
    -> done

--
```

If I have a list of items that need to be done, I'll organize them in a `do` list:

```
do now
  - do the first thing
  - do the second thing
  - do the third thing
```

As I cross them off, I use the same `-> done` notation:

```
do now
  - do the first thing
    -> done
  - do the second thing
    -> done
  - do the third thing
```

That's it! This lightweight note-taking structure has been a big help to me over the years. I hope it's useful for you too.