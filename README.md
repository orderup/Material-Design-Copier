# Material-Design-Copier
A python script to copy content from a google material design folder into your android project. Requires python 2.7.7+ (python with argparse essentially)

#Usage

1. Clone this repository and change to it
2. Run `cd git submodule init && git submodule update`
3. Add executable permission: `chmod +x material-copy.py`
4. Run `./material-copy.py <group> <name> <color> <size> <dest>`

#Example:
```
Material-Design-Copier$ ./material-copy.py navigation close black 48 /tmp
('Copying', 'material-design-icons/navigation/drawable-hdpi/ic_close_black_48dp.png', 'to', '/tmp/drawable-hdpi/ic_close_black_48dp.png')
('Copying', 'material-design-icons/navigation/drawable-mdpi/ic_close_black_48dp.png', 'to', '/tmp/drawable-mdpi/ic_close_black_48dp.png')
('Copying', 'material-design-icons/navigation/drawable-xhdpi/ic_close_black_48dp.png', 'to', '/tmp/drawable-xhdpi/ic_close_black_48dp.png')
('Copying', 'material-design-icons/navigation/drawable-xxhdpi/ic_close_black_48dp.png', 'to', '/tmp/drawable-xxhdpi/ic_close_black_48dp.png')
('Copying', 'material-design-icons/navigation/drawable-xxxhdpi/ic_close_black_48dp.png', 'to', '/tmp/drawable-xxxhdpi/ic_close_black_48dp.png')
```
