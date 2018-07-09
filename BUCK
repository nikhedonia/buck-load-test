print("ROOT")

genrule(
  name = 'main',
  out = 'main',
  cmd = 'cat $(location main//:main) > main',
  srcs = []
)
