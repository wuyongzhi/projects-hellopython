---
name: 'Testing overview'
about: 'This is used by the DataCamp Projects team and should not be used by instructors.'

---

@_______, here is some help for completing the tests:

### Overview of testing

For DataCamp projects, we don't need to and can't possibly test _everything_. We just need to give students some help along the way. It is difficult/impossible to test things not saved to objects and cells with multiple plots. And that's okay!

Testing in Python is done using the nose framework. Here's a model example of testing in a project for you to peruse: [Up and Down With the Kardashians](https://drive.google.com/open?id=1fd7A96FY-F27WEogw-Wpdh_1zi-iTQKq)

### Testing your tests

Ensure your tests pass in your local environment by processing a solution code cell then its tests back to back. Here's a video of me demo-ing that for another instructor:

https://www.useloom.com/share/1dc647f7b58340cfa7adcadf5244937b

Ensure your tests pass in the DataCamp environment by inspecting your Project's `develop` branch's build log, which is in the first link in this GitHub repo's `README.md`. If tests pass locally but not on DataCamp, there is likely an issue with the installations in `requirement.sh`. Try to fix it yourself, then reach out to me if you're stuck (this happens fairly often as some of the installation info is removed from the view of instructors).
