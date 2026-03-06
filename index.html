import React, { useState } from 'react';
import { TreeDeciduous, Info, Ban, Globe, MapPin, ChevronRight, User, Camera, ImageOff } from 'lucide-react';

const MentefactoApp = () => {
  const [activeSection, setActiveSection] = useState(null);

  const sections = {
    superordinate: {
      title: "Global Environmental Degradation",
      icon: <Globe className="w-6 h-6" />,
      content: "Deforestation is a major sub-category of environmental degradation. It represents a significant threat to global climate stability and is a primary driver of the current ecological crisis.",
      details: ["Anthropogenic Climate Change", "Ecosystem Services Depletion", "Global Biodiversity Loss"]
    },
    isoordinate: {
      title: "Key Characteristics",
      icon: <Info className="w-6 h-6" />,
      content: "The process is defined by the permanent removal of forest cover. Unlike temporary changes, it results in long-term structural shifts in the landscape and its biological functions.",
      details: ["Permanent Canopy Loss", "Fragmented Habitats", "Disrupted Nutrient Cycling", "Increased Carbon Footprint"]
    },
    exclusion: {
      title: "Exclusions",
      icon: <Ban className="w-6 h-6" />,
      content: "It is essential to distinguish deforestation from other forms of land or forest management that do not imply permanent destruction.",
      details: ["Sustainable Silviculture", "Natural Forest Regeneration", "Reforestation Programs", "Small-scale Agroforestry"]
    },
    infraordinate: {
      title: "Local Manifestations (Colombia)",
      icon: <MapPin className="w-6 h-6" />,
      content: "In the Colombian context, deforestation occurs through specific illegal and economic activities that target strategic ecosystems.",
      details: ["Unregulated Cattle Ranching", "Illegal Timber Extraction", "Expansion of Agricultural Frontiers", "Infrastructure Development"]
    }
  };

  const SectionCard = ({ type, data }) => (
    <div 
      onClick={() => setActiveSection(activeSection === type ? null : type)}
      className={`p-5 rounded-2xl border transition-all cursor-pointer shadow-sm ${
        activeSection === type ? 'border-green-600 bg-green-50 shadow-md' : 'border-gray-200 bg-white hover:border-green-400'
      }`}
    >
      <div className="flex items-center gap-3 mb-3">
        <div className={`p-2 rounded-lg ${activeSection === type ? 'bg-green-600 text-white' : 'bg-gray-100 text-gray-500'}`}>
          {data.icon}
        </div>
        <h3 className="font-bold text-gray-800 tracking-tight">{data.title}</h3>
      </div>
      <p className="text-sm text-gray-600 leading-relaxed mb-3">
        {data.content}
      </p>
      {activeSection === type && (
        <div className="space-y-2 border-t border-gray-100 pt-3 animate-in fade-in slide-in-from-top-1">
          {data.details.map((item, i) => (
            <div key={i} className="flex items-center gap-2 text-xs font-semibold text-green-700">
              <ChevronRight size={14} />
              {item}
            </div>
          ))}
        </div>
      )}
    </div>
  );

  const ImagePlaceholder = ({ src, alt, title, description }) => {
    const [error, setError] = useState(false);

    return (
      <div className="group">
        <div className="aspect-video bg-gray-100 rounded-2xl overflow-hidden mb-4 shadow-sm border border-gray-200 flex items-center justify-center relative">
          {error ? (
            <div className="flex flex-col items-center text-gray-400 p-4 text-center">
              <ImageOff size={40} className="mb-2" />
              <p className="text-[10px] font-bold uppercase tracking-widest">Image unavailable</p>
            </div>
          ) : (
            <img 
              src={src} 
              alt={alt} 
              onError={() => setError(true)}
              className="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
            />
          )}
        </div>
        <h4 className="font-bold text-gray-800 text-sm uppercase mb-1">{title}</h4>
        <p className="text-xs text-gray-500 leading-relaxed">{description}</p>
      </div>
    );
  };

  return (
    <div className="min-h-screen bg-white p-6 md:p-12 font-sans text-gray-900">
      <div className="max-w-6xl mx-auto">
        
        {/* Header simple con solo el nombre */}
        <div className="border-b-2 border-gray-100 pb-8 mb-12 flex flex-col md:flex-row justify-between items-end">
          <div>
            <h1 className="text-3xl font-light text-gray-500 uppercase tracking-[0.2em] mb-1">Mentefacto</h1>
            <h2 className="text-4xl font-black text-gray-900 tracking-tighter uppercase">Deforestation</h2>
          </div>
          <div className="text-right mt-4 md:mt-0">
            <p className="text-lg font-bold text-green-700 uppercase tracking-wider">Luis Duarte</p>
          </div>
        </div>

        {/* Estructura del Mentefacto */}
        <div className="grid grid-cols-1 md:grid-cols-3 gap-8 items-center relative">
          <div className="md:col-start-2">
            <SectionCard type="superordinate" data={sections.superordinate} />
          </div>

          <div className="md:row-start-2">
            <SectionCard type="isoordinate" data={sections.isoordinate} />
          </div>

          <div className="md:row-start-2 flex justify-center p-4">
            <div className="w-44 h-44 bg-green-600 rounded-3xl shadow-xl flex flex-col items-center justify-center text-white p-6 transform hover:scale-105 transition-transform">
              <TreeDeciduous size={48} className="mb-2" />
              <span className="text-xs font-bold tracking-widest opacity-80 uppercase">Concept</span>
              <span className="text-xl font-black uppercase">Forestry Loss</span>
            </div>
          </div>

          <div className="md:row-start-2">
            <SectionCard type="exclusion" data={sections.exclusion} />
          </div>

          <div className="md:col-start-2 md:row-start-3">
            <SectionCard type="infraordinate" data={sections.infraordinate} />
          </div>
        </div>

        {/* Área de evidencia visual con prevención de errores 404 */}
        <div className="mt-20">
          <div className="flex items-center gap-2 mb-8 border-l-4 border-green-600 pl-4">
            <Camera className="text-green-600" size={20} />
            <h3 className="text-xl font-bold text-gray-800 uppercase tracking-tight">Environmental Case Study: Colombia</h3>
          </div>
          
          <div className="grid grid-cols-1 md:grid-cols-2 gap-8">
            <ImagePlaceholder 
              src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e?w=800&q=80"
              alt="Bosque Conservado"
              title="Figure 1: Biodiversity Hotspots"
              description="Strategic forest regions in Colombia facing high risk of land conversion."
            />
            <ImagePlaceholder 
              src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=800&q=80"
              alt="Impacto Ambiental"
              title="Figure 2: Landscape Alteration"
              description="Documentation of ecological shifts due to illegal cattle ranching and farming expansion."
            />
          </div>
        </div>

        {/* Footer minimalista */}
        <div className="mt-20 pt-8 border-t border-gray-100 flex justify-center items-center text-[10px] font-bold text-gray-400 tracking-[0.3em] uppercase">
          <span>Luis Duarte • 2024</span>
        </div>
      </div>
    </div>
  );
};

export default MentefactoApp;
