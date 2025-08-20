## Test Cases

**Test 1 : Nothing happening**
- Expected: Gate up, light/bell off
- Actual: as expected

**Test 2: Train approach**
- Expected: Sents command to lower the gate, turn light/bell on
- Actual: Motor drives gate down and turn light/bell on

**Test 3: Train on crossing**
- Expected: Gate stays down with light/bell on
- Actual: as expected
  
**Test 4: 3 second clear check**
- Expected: raise the gate, light/bell are off
- Actual: After 3 secs, all clear, raises the gate and turns light/bell off
