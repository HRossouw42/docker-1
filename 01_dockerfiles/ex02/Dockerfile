# BUILDING: -t ft-rails:on-build ./ft-rails
# BUILDING2: -t ex02 .
# RUNNING: -p 3000:3000 -i -d ex02

# Generic file that calls in ft_rails, as required by the exercise

FROM ft-rails:on-build
EXPOSE 3000
CMD ["rails", "s", "-b", "0.0.0.0", "-p", "3000"]
