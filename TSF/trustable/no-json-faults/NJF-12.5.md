---
level: 1.1
normative: true

references:
        - type: cpp_test
          name: "accept;noncharacter code positions"
          path: "TSF/tests/unit-strings.cpp"
        - type: cpp_test
          name: "Unicode;unescaped unicode"
          path: "TSF/tests/unit-strings.cpp"
evidence:
  type: check_test_results
  configuration:
    tests: 
        - strings
score:
    Jonas-Kirchhoff: 0.75
    Erikhu1: 1.0
---

The service accepts Non-Characters.