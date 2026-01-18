# Traceability Matrix Student Marks Management System

Purpose : Map requirements (user stories) to implementation and tests, and show when each was delivered.

| Req ID | User Story | Sprint | Implementation ( Code ) | Verification (Tests ) | Release Tag | Status |
| US1 | Add a student | Sprint -1 | ‘src/app.py‘->‘MarksSystem.add_student()‘ | ‘tests/test_app.py‘->‘test_add_student_success‘,‘test_add_student_duplicate ‘,
‘test_add_student_missing_fields‘ | v0.1 | Done |
| US2 | Add marks | Sprint -1 | ‘src/app.py‘->‘MarksSystem.add_marks()‘ | ‘tests/test_app.py‘->‘test_add_marks_success‘,‘test_add_marks_out_of_range‘,
‘test_add_marks_unknown_student‘ | v0.1 | Done | 
| US3 | Calculate grade | Sprint -2 | ‘src/app.py‘->‘MarksSystem.calculate_grade()‘ | ‘tests/test_app.py‘->‘test_calculate_grade_A_plus‘, 
‘test_calculate_grade_boundaries‘, ‘test_calculate_grade_marks_not_set‘ | v0 .2 | Done |
| US4 | Generate report | Sprint -3 |                    |                       |             | Planned |
