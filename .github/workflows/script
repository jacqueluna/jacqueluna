from lxml import etree

def process_xml(input_file, output_file):
    parser = etree.XMLParser(xinclude=True)
    tree = etree.parse(input_file, parser)
    tree.xinclude()
    tree.write(output_file)

process_xml('academiaXpathD.xml', 'academiaprocesado.xml')
