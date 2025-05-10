% Test Harness
test_all_sorts(Input) :-
    write('Original List: '), writeln(Input),

    bubble_sort(Input, B), write('Bubble Sort: '), writeln(B),
    insertion_sort(Input, I), write('Insertion Sort: '), writeln(I),
    selection_sort(Input, S), write('Selection Sort: '), writeln(S),
    merge_sort(Input, M), write('Merge Sort: '), writeln(M),
    quick_sort(Input, Q), write('Quick Sort: '), writeln(Q),
    heap_sort(Input, H), write('Heap Sort: '), writeln(H),
    counting_sort(Input, C), write('Counting Sort: '), writeln(C).


% Example usage:
% ?- test_all_sorts([5, 3, 8, 1, 3]).



% Result of Sorting_Techniques.....
/*
test_all_sorting techniques..
Original List: [5,3,8,1,3]
Bubble Sort: [1,3,3,5,8]
Insertion Sort: [1,3,3,5,8]
Selection Sort: [1,3,3,5,8]
Merge Sort: [1,3,3,5,8]
Quick Sort: [1,3,3,5,8]
Heap Sort: [1,3,5,8]
Counting Sort: [1,3,3,5,8]
true
*/
