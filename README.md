Sources for photos used: 

- Dog: [Karseten Winegeart on Unsplash](https://unsplash.com/photos/5PVXkqt2s9k)
- Cat: [Alvan Nee on Unsplash](https://unsplash.com/photos/ZCHj_2lJP00)
- Rabbit: [Emiliano Vittoriosi on Unsplash](https://unsplash.com/photos/3FSBkX4yG80)
@bp.route('/<int:pet_id>’)
def show(pet_id): 
    pet = pets[id - 1]
    return render_template('show.html', pet=pet)