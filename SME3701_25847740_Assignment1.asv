

% Parameters
m = 5;          % mass (kg)
k = 2000;       % stiffness (N/m)
x0 = 0.02;      % initial displacement (m)
v0 = 0;         % initial velocity (m/s)

% Question1.1 Natural frequency
wn = sqrt(k/m); % wn = sqrt(2000/5); and when running simulation answer is 20rad/s

% Time vector
t = linspace(0,5,1000);

% Question1.2 Displacement
x = x0 * cos(wn * t);

% Question1.3 Plot displacement
figure(1);
plot(t, x, 'b', 'LineWidth', 2);
xlabel('Time (s)');
ylabel('Displacement (m)');
title('Displacement vs Time');
grid on;

% Question 1.4
% Velocity
v = -x0 * wn * sin(wn * t);
% Plot velocity
figure(2);
plot(t, v, 'r', 'LineWidth', 2);
xlabel('Time (s)');
ylabel('Velocity (m/s)');
title('Velocity vs Time');
grid on;