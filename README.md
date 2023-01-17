# curso_enero_2023


amino2 = ['Alaline', 'Arginine', 'Cysteine', 'Glutamine', 'Glycine',
 'Histidine', 'Lysine', 'Methionine', 'Phenilalanine', 'Proline',
 'Serine', 'Valine']
 
 amino_dict.update({'H': ('His', 'Histidine', 'No polar', 5739,
                         {'DB': 'PubChem'}, {'Humanos':'Esencial', 'Bacterias': 'No esencial'})})

for var in sec:
    gc = (dict(Counter(var))['c'] + dict(Counter(var))['g'])/len(var)
    print(round(gc * 100, 2), var)
