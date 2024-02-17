class TestParseExpenses (unittest.TestCase):
def
test_parse_expenses_with_valid_input(self
expenses_string
=
'2023-01-02 -34.01 USD\
[(datetime.datetime (2023
expected_output = self.assertEqual(parse_expenses(expenses
def test_parse_expenses_with_empty_input(self
expenses_string
expected_output
=
= [ ]
self.assertEqual(parse_expenses(expenses_
'__main__':
if name
unittest.main()