<!DOCTYPE html>
<html lang="en">

{% include head.md %}

<body style="display: flex;
      min-height: 100vh;
      flex-direction: column;">
{% include header.md %}
<main style="flex: 1 0 auto; font-family: 'Sanchez', sans">
{{ content }}
</main>
{% include footer.md %}
</body>

</html>