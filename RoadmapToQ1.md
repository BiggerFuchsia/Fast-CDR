Progress toward Quality Level 1
=============================

# Current Status Summary Comparison

The chart below compares *eprosima Fast DDS* current Quality Level with Quality Levels 1 through 5 relative to the
'Level 1' requirements' 

✓ = required

● = recommended

○ = optional

☓ = requirement currently unmet

■ = requirement partially fulfilled 

| Number  |                    Requirement                    |   Current State    | Level 1 | Level 2 | Level 3 | Level 4 | Level 5 |
| ------- | ------------------------------------------------- | ------------------ | ------- | ------- | ------- | ------- | ------- |
| 1       | **Version policy**                                |                    |         |         |         |         |         |
| 1.i     | Version Policy available                          | x                  | ✓       | ✓       | ✓       | ●       |         |
| 1.ii    | Stable version                                    | ✓                  | ✓       | ✓       | ✓       |         |         |
| 1.iii   | Declared public API                               | ■                  | ✓       | ✓       | ●       |         |         |
| 1.iv    | API stability policy                              | ✓                  | ✓       | ✓       | ✓       |         |         |
| 1.v     | ABI stability policy                              | ✓                  | ✓       | ✓       | ✓       |         |         |
| 1.vi    | API/ABI stable within ROS distribution            | ✓                  | ✓       | ✓       | ●       |         |         |
| 2       | **Change control process**                        |                    |         |         |         |         |         |
| 2.i     | All changes occur on change request               | ■                  | ✓       | ✓       | ✓       | ●       |         |
| 2.ii    | Contributor origin (DCO, CLA, etc)                | ✓                  | ✓       | ✓       |         |         |         |
| 2.iii   | Peer review policy                                | ✓                  | ✓       |         |         |         |         |
| 2.iv    | CI policy for change requests                     | ✓                  | ✓       | ✓       | ✓       |         |         |
| 2.v     | Documentation policy for change requests          | x                  | ✓       |         |         |         |         |
| 3       | **Documentation**                                 |                    |         |         |         |         |         |
| 3.i     | Per feature documentation                         | ✓                  | ✓       | ✓       |         |         |         |
| 3.ii    | Per public API item documentation                 | ✓                  | ✓       |         |         |         |         |
| 3.iii   | Declared License(s)                               | ✓                  | ✓       | ✓       | ✓       | ✓       | ●       |
| 3.iv    | Copyright in source files                         | ✓                  | ✓       | ✓       | ✓       | ✓       |         |
| 3.v     | Quality Declaration                               | ■                  | ✓       | ✓       | ○       |         |         |
| 3.v.a   | Quality declaration linked to README              | ■                  | ✓       | ✓       | ✓       |         |         |
| 3.v.b   | Centralized declaration available for peer review | ■                  | ●       | ●       | ○       |         |         |
| 3.v.c   | Lists and Peer Review                             | ■                  | ✓       | ✓       | ✓       |         |         |
| 4       | **Testing**                                       |                    |         |         |         |         |         |
| 4.i     | Feature items tests                               | ✓                  | ✓       | ✓       | ●       | ●       |         |
| 4.ii    | Public API tests                                  | ✓                  | ✓       |         |         |         |         |
| 4.iii.a | Using coverage                                    | x                  | ✓       | ✓       |         |         |         |
| 4.iii.a | Coverage policy                                   | x                  | ✓       |         |         |         |         |
| 4.iv.a  | Performance tests (if applicable)                 | ✓ (not applicable) | ✓       |         |         |         |         |
| 4.iv.b  | Performance tests policy                          | ✓ (not applicable) | ✓       |         |         |         |         |
| 4.v.a   | Code style enforcement (linters)                  | x                  | ✓       | ✓       |         |         |         |
| 4.v.b   | Use of static analysis tools                      | x                  | ✓       | ✓       |         |         |         |
| 5       | **Dependencies**                                  |                    |         |         |         |         |         |
| 5.i     | Must not have ROS lower level dependencies        | ✓                  | ✓       | ✓       |         |         |         |
| 5.ii    | Optional ROS lower level dependencies             | ✓                  | ○       | ○       | ○       |         |         |
| 5.iii   | Justifies quality use of non-ROS dependencies     | ✓                  | ✓       | ✓       |         |         |         |
| 6       | **Platform support**                              |                    |         |         |         |         |         |
| 6.i     | Support targets Tier1 ROS platforms               | ■                  | ✓       | ✓       | ✓       | ●       |         |
| 7       | **Security**                                      |                    |         |         |         |         |         |
| 7.i     | Vulnerability Disclosure Policy                   | x                  | ✓       | ✓       | ●       |         |         |


## Progress toward Quality Level 3

### 1 Version policy
- [ ] Version Policy available

### 2
- [ ] Documentation policy for change requests


### 3 Documentation
- [ ] Check documentation
- [ ] Revamp README.md
- [ ] Quality Declaration
- [ ] Quality declaration linked to README

### 4 Testing
#### Code style enforcement (linters)

- [x] Apply uncrustify with [config file](https://github.com/eProsima/cpp-style)
- [ ] Add code style check to CI 
- [ ] Add fas-CDR to Synopsys Coverity

### 5 Platform support

- [x] Check dependencies

### 6 Platform support

- [ ] Supported platform document
- [ ] Check mac support

### 7 Security
- [ ] Link to Vulnerability Disclosure Policy


