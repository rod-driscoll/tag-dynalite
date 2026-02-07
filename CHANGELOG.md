# 2.4

- Resolved an issue where the maximum area number was incorrectly set to 250 instead of 255.
- Added `Preset Recall Mode` property option to use opcodes `01` - `04` and `0A` - `0D` for preset recall (`Non-Linear`) instead of opcode `65` (`Linear`).

# 2.6

- Improved buffer handling to allow for fragments.

# 2.6.2

-- 20260207 Rod Driscoll<rod@theavitgroup.com.au>
  -- improved buffer parsing, including [0xAC] Physical responses
  -- added presetTimer to query levels after a preset is finished executing
  -- reduced minimum "Poll Rate (s)" from 60 to 20
