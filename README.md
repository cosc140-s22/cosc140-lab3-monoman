# COSC140 lab 3

## Answers to the five questions at the end of the lab description

1. Product.objects.create(name = "stuffed shark", description = "soft, but with pointy teeth", price = "45.00", minimum_age_appropriate = "2", maximum_age_appropriate = "43")

2. Product.objects.all()

3. p1 = Product.objects.get(id=6)
   p1.price = 22.50
   p1.save()

4. p1 = Product.objects.get(id=6)
5. p1.delete()
   The ID will be None?
   
7.  objects = Product.objects.filter(name__icontains ='stuff').filter(price__lt = "10")

## Lab feedback

 * How long did you spend on this lab?
 * 45 minutes

 * What did you think about it?  What was good?  What could be improved?
 * I liked it

## Feedback

S

Nicely done!

