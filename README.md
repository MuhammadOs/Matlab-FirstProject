# Matlab-FirstProject
%% (Q1) A=[-7 5 -9;2 -1 2;1 -1 2]; B=[16 3 2 13;5 10 11 8; 9 6 7 12;4 15 14 1]; C=[4 2 -3;7 -7 9;3 -5 6]; D=[6 3 2;2 12 -7;-1 6 2;-5 15 11];  3A - 5C %{ ans = -41 5 -12 -29 32 -39 -12 22 -24 %}  7A+2B %{ Error using + Matrix dimensions must agree. %}  C*A %{ ans = -27 21 -38 -54 33 -59 -25 14 -25 %}  CD' %{ ans = 24 53 2 -23 39 -133 -31 -41 15 -96 -21 -24 %} %% (Q2) %zeros(n) %makes matrix nn all of it items is 0s. %zeros(3) %ans =  % 0 0 0 % 0 0 0 % 0 0 0 %zeros(m,n) %makes matrix mn all of it items is 0s. % zeros(3,4) % % ans = % % 0 0 0 0 % 0 0 0 0 % 0 0 0 0 %ones(n) %makes matrix nn all of it items is 1s. % ones(4) % % ans = % % 1 1 1 1 % 1 1 1 1 % 1 1 1 1 % 1 1 1 1 %ones(mn) %makes matrix mn all of it items is 1s. % ones(4,5) % % ans = % % 1 1 1 1 1 % 1 1 1 1 1 % 1 1 1 1 1 % 1 1 1 1 1 %size(D) %show us the dimensions of matrix D % size(D) % % ans = % % 4 3 %zeros(size(D)) %makes matrix with dimensions of matrix D all of it items is 0s. % zeros(size(D)) % % ans = % % 0 0 0 % 0 0 0 % 0 0 0 % 0 0 0 %diag[1 2 3 4] %make matrix all of it items is 0s but the diagnal is 1 2 3 4. % diag([1 2 3 4]) % % ans = % % 1 0 0 0 % 0 2 0 0 % 0 0 3 0 % 0 0 0 4 %eye(n) %make for us matrix n*n but the items is 0s and the diagnal is 1s. % eye(5) % % ans = % % 1 0 0 0 0 % 0 1 0 0 0 % 0 0 1 0 0 % 0 0 0 1 0 % 0 0 0 0 1 %% (Q3) % [A,B] % Error using horzcat % Dimensions of matrices being concatenated % are not consistent. % % [A;B] % Error using vertcat % Dimensions of matrices being concatenated % are not consistent. %% (Q4) list=[eye(7,7),[5;5;5;5;5;5;5]] %{ list = 1 0 0 0 0 0 0 5 0 1 0 0 0 0 0 5 0 0 1 0 0 0 0 5 0 0 0 1 0 0 0 5 0 0 0 0 1 0 0 5 0 0 0 0 0 1 0 5 0 0 0 0 0 0 1 5 %} % A(i,:) %Subscript indices must either be real %positive integers or logicals. %if (i) integer numbr %A(i,:) %it well show us all of items of row n. %A(:,j) %Subscript indices must either be real %positive integers or logicals.  %if (j) integer numbr %A(:,j) %it well show us all of items of clumn j. %by Muhammad Osama Abdelgelil- 3b
