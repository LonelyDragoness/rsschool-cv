# CV - **Anton Taberka** 

### Contact Info
**Discord:** BanShe#7062

[**Github**](https://github.com/LonelyDragoness)

[**Vk.com**](https://vk.com/midnight_pulse)

**Telegram:** @SoulHowl

**Phone number:** +375 297225069

_**The easiest way to find me, if i'm online and available, is either via Discord, or Telegram.**_

<hr>

### Skills

**Python.** Scripts for processing data, automating daily tasks.

**Django and flask frameworks.** Newbie level, can create simple back-end for web apps.

**HTML&CSS.** Basic understanding, enough for common usage.

**Git.** Used for projects during the studies.

**SQL.** Simple work with tables and databases (predominantly MySQL, PostgreSQL).

**Ruby.** Used for some web scraping.

**JavaScript** Basic language knowledge.

<hr>

### Code example _(snippet of Ruby code)_
```ruby
  begin
    $counter = 0
    CSV.open("#{$csv_name}", "a+") do |csv|
      if product_price[0].length == 1
        full_name = $product_name + " - " + product_quantity.first[0]
        csv << [full_name, product_price.first.map { |x| x[/\d\d?.\d\d?/]}[0], product_image]

      else
        (0..product_price.length).each do |num|
          full_name = $product_name + " - " + product_quantity.first[num]
          clean_price = product_price.first.map { |x| x[/\d\d?.\d\d?/]}
          csv << [full_name, clean_price[num], product_image]
        end
      end
    end
  rescue
    $counter = 1
  end

```

<hr>

### Languages _(according to various tests and personal feeling)_
**Russian:**  C2. Native.

**English:** In-between B2 and C1. Can communicate, read, write, translate freely most of the time.

**German:** A1. Beginner, learning.

<hr>

### Experience
I don't have any commercial coding experience, but i'm actively self-educating for the last 1.5 years, using 
various web resources and books (No Starch Press, W3Schools, etc.)

<hr>

### About me
I'm eager to think out of the box and learn new things, not afraid of a challenge. 
Being able to stay calm under the pressure. Both capable of playing in a team and working individually.

Actively learning CG illustration, 3d animation and new technologies in my free time.

Also, i'm a dragon ~~(just kidding)~~.
