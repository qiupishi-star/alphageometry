a b c = triangle a b c;
d = on_line b c;
e = on_line a c;
x y = length;
check_length a e x;
check_length b c x;
check_length e c y;
check_length c d y;
check_length a b (x + y);
check_length a c (x + y);
check_length b d (x + y);
check_length d e (x + y);
? angle e c d
