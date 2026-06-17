# Music Library Design Template 

## 1. Describe the Problem

- As a user, So that I can keep track of my music listening,
I want to add tracks I've listened to and see a list of them.

Clarifying notes:
State:

Behaviours:
functions: 
-add_track
-list_tracks 


## 2. Design the Class Interface

_Include the initializer, public properties, and public methods with all parameters, return values, and side-effects._

```python

class MusicLibrary:
    # User-facing properties:
    #   name: string

    def __init__(self):
        # Parameters:
        #  None 
        # Side effects:
        #   None 
        pass 

    def add_track(self, track):
        # Parameters:
        #   track: string representing a single track
        # Returns:
        #   Nothing
        # Side-effects:
        #   Saves the track to the self object
        pass 

    def track_list(self):
        # Returns:
        # a list of listened to tracks
        # Side-effects:
        # None
        pass 
```

## 3. Create Examples as Tests

``` python

# Given a track 
# MusicLibrary adds track to the tracks list 

track_1 = MusicLibrary()
track_1.add_track("Hello")
assert self.tracks == []  # => ["Book dentist appointment"]

# Given an added track 
# track_list returns the tracks from the list

track_1 = MusicLibrary()
track_2 = MusicLibrary()
track_1.add_track("Hello")
track_2.add_track("Hello, Goodbye")
assert MusicLibrary.track_list() == ["Hello", "Hello, Goodbye"]


## 4. Implement the Behaviour

_After each test you write, follow the test-driving process of red, green, refactor to implement the behaviour._
